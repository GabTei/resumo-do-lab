# Computação e Rede:

## Tipos de Computação:

**Máquinas Virtuais (VMs):** Executam sistemas operacionais completos na nuvem e oferecem controle total da infraestrutura.
**Instâncias de Contêiner:** Executam aplicações empacotadas de forma leve e rápida, compartilhando o sistema operacional do host.
**Functions:** Executam código sob demanda (serverless), rodando apenas quando acionadas e cobrando apenas pelo uso.

## Hospedagem de Aplicativos:

Refere-se às opções de executar aplicações na nuvem sem precisar gerenciar servidores físicos. Plataformas gerenciadas permitem implantar aplicativos web, APIs e serviços rapidamente. Isso reduz a complexidade operacional e melhora a escalabilidade.

# Opções de VM (IaaS):

## VMs:

Máquinas Virtuais são computadores completos executando na nuvem. Elas permitem instalar sistemas operacionais, softwares e configurações personalizadas. São usadas quando se precisa de maior controle sobre o ambiente.

## Conjuntos de Dimensionamento:

Permitem criar e gerenciar **várias VMs idênticas automaticamente**. A quantidade de máquinas pode aumentar ou diminuir conforme a demanda. Isso ajuda a manter desempenho e alta disponibilidade.

## Conjuntos de Disponibilidade:

Distribuem VMs para evitar falhas simultâneas. Garantem maior disponibilidade das aplicações. Utilizam **domínios de falha e domínios de atualização**.

### Domínio de Falha:

Representa um grupo de recursos que compartilham o mesmo hardware físico. Se ocorrer falha de energia ou hardware, apenas aquele domínio é afetado. Outras VMs continuam funcionando.

### Domínio de Atualização:

Agrupa recursos que serão atualizados ao mesmo tempo. Durante manutenção do sistema, apenas um domínio é atualizado por vez. Isso evita indisponibilidade total da aplicação.

## Área de Trabalho Virtual:

Permite acessar desktops e aplicativos Windows pela nuvem. Usuários podem trabalhar remotamente de qualquer dispositivo. Facilita gerenciamento centralizado e segurança corporativa.

# Serviços de Contêiner (PaaS):

## Instâncias de Contêiner:

Executam contêineres rapidamente sem necessidade de gerenciar servidores. São ideais para aplicações simples ou tarefas isoladas. Escalam rapidamente e iniciam em poucos segundos.

## Aplicativos de Contêiner:

Permitem executar aplicações baseadas em contêiner com escalabilidade automática. Facilitam a implantação de microserviços. Integram-se facilmente com outras soluções de nuvem.

## Kubernetes:

Plataforma para **orquestração de contêineres em grande escala**. Gerencia implantação, escalabilidade e disponibilidade dos contêineres. Muito usado em arquiteturas de microserviços.

## Functions:

Executam código baseado em eventos sem necessidade de servidores. Escalam automaticamente conforme a demanda. Ideais para automação, APIs simples e processamento de eventos.

# VNet (Redes Virtuais):

## Redes Virtuais:

Permitem criar redes privadas dentro da nuvem. Conectam recursos como VMs, bancos de dados e serviços. Funcionam de forma semelhante a redes tradicionais de datacenter.

## Endpoints Público e Privado:

- **Endpoint Público:** Permite acesso ao serviço pela internet.
- **Endpoint Privado:** Conecta serviços dentro da rede privada da nuvem. Isso aumenta a segurança e o controle de acesso.

## Sub-Redes:

Dividem uma rede virtual em partes menores. Permitem organizar e isolar recursos dentro da rede. Ajudam na segurança e no gerenciamento do tráfego.

## Peering:

Permite conectar duas redes virtuais diretamente. A comunicação ocorre com **baixa latência e alta velocidade**. É usado para integrar diferentes ambientes na nuvem.

# Conectividade:

## Gateway de VPN:

Permite conectar redes locais ao ambiente de nuvem por meio da internet. A conexão é protegida por criptografia. Muito usado para integração entre datacenter e nuvem.

## ExpressRoute:

Cria uma conexão **privada dedicada** entre a rede local e a nuvem. Não utiliza a internet pública. Oferece maior segurança, confiabilidade e menor latência.

# DNS Azure:

É o serviço de resolução de nomes de domínio na nuvem. Converte nomes de sites em endereços IP. Permite gerenciar domínios e registros DNS de forma escalável.
