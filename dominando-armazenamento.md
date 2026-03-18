# Armazenamento

## Storage Account

É a conta principal que contém todos os serviços de armazenamento do Azure. Funciona como um contêiner para dados como arquivos, blobs, filas e tabelas. Define configurações como região, desempenho e redundância.

## Redundância de Armazenamento

Garante cópias dos dados para alta disponibilidade e durabilidade. **LRS** mantém dados em um único datacenter, enquanto **ZRS** replica entre zonas. **GRS/GZRS** replicam para outra região, e versões **RA** permitem leitura na região secundária.

## Serviços de Armazenamento + Managed Disks

**Blob** armazena dados não estruturados (imagens, vídeos, backups). **File** oferece compartilhamento de arquivos acessível via rede, **Queue** gerencia mensagens e **Table** armazena dados NoSQL. **Managed Disks** são discos gerenciados usados por máquinas virtuais.

## Pontos de Extremidade Públicos

São URLs usados para acessar os serviços de armazenamento pela internet. Permitem que aplicações e usuários acessem dados remotamente. Podem ser protegidos com autenticação e regras de firewall.

## Camadas de Acesso

Definem o custo e frequência de acesso aos dados armazenados. **Hot** é para dados acessados frequentemente, **Cool/Cold** para acesso menos frequente. **Archive** é para longo prazo com baixo custo, e **Smart** ajusta automaticamente conforme o uso.

## Migração de Dados

Processo de mover dados locais ou de outros sistemas para a nuvem. Pode ser feito via rede ou fisicamente, dependendo do volume de dados. Ferramentas ajudam a tornar o processo mais rápido e seguro.

### Data Box

Dispositivo físico enviado pela Microsoft para transferir grandes volumes de dados. Ideal quando a internet é lenta ou o volume é muito grande. Os dados são enviados ao datacenter após o uso.

### AzCopy

Ferramenta de linha de comando para copiar dados rapidamente para o Azure. Suporta transferência entre local e nuvem ou entre contas. É eficiente e automatizável.

### Gerenciador de Armazenamento

Ferramenta gráfica para gerenciar dados no Azure. Permite upload, download e organização de arquivos. Facilita o uso para quem prefere interface visual.

### Sincronização de Arquivos

Mantém arquivos locais sincronizados com o Azure. Permite acesso híbrido (local + nuvem). Muito útil para continuidade e backup de dados.
