# Componentes de Arquitetura do Azure:

**Hierarquia de Gerenciamento:**

- **Grupos de Gerenciamento:** São o nível mais alto de organização no Microsoft Azure. Permitem agrupar várias assinaturas para aplicar políticas e controles de forma centralizada. Facilitam a governança em grandes ambientes.

- **Assinaturas:** Representam um acordo para usar os serviços do Azure. Servem para organizar recursos e controlar cobrança e acesso. Cada assinatura pode conter vários grupos de recursos.

- **Grupos de Recursos:** São contêineres lógicos que organizam recursos relacionados. Permitem gerenciar, monitorar e controlar permissões para vários recursos juntos. Cada recurso pertence a apenas um grupo de recursos.

- **Recursos:** São os serviços individuais criados no Azure, como máquinas virtuais, bancos de dados e redes. Eles realizam as funções reais das aplicações. Todos os recursos precisam estar dentro de um grupo de recursos.

- **Etiquetas:** São pares de chave e valor usados para identificar e organizar recursos. Ajudam no controle de custos, organização e automação. Permitem filtrar e gerenciar recursos com mais facilidade.
