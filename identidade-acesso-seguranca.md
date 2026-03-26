# Identidade, Acesso e Segurança

## Microsoft Entra ID

O Microsoft Entra ID é o serviço central de identidade na nuvem. Ele gerencia usuários, grupos, aplicativos e permissões de acesso. Permite autenticação segura e controle de quem acessa o quê.

## Authentication (Autenticação)

É o processo de verificar **quem você é**. Geralmente envolve login com usuário e senha, podendo incluir outros fatores. É o primeiro passo antes de conceder acesso a qualquer sistema.

## Authorization (Autorização)

Define **o que você pode acessar** após se autenticar. Controla permissões e níveis de acesso a recursos. Garante que usuários só acessem o que têm direito.

## MFA (Autenticação Multifator)

Adiciona uma camada extra de segurança ao login. Exige mais de um fator, como senha + código no celular. Reduz muito o risco de acesso indevido.

## SSO (Single Sign-On)

Permite acessar vários sistemas com um único login. Evita múltiplas autenticações repetidas. Melhora a experiência do usuário e a produtividade.

## Managed Identity

O Azure Managed Identity fornece identidade automática para recursos do Azure. Elimina a necessidade de armazenar senhas no código. Permite que serviços se autentiquem de forma segura.

## Domain Services

O Azure AD Domain Services oferece um domínio gerenciado na nuvem. Suporta protocolos tradicionais como LDAP e Kerberos. Permite usar aplicações legadas sem gerenciar servidores de domínio.

## External ID

Permite gerenciar identidades de usuários externos (clientes/parceiros). Suporta login com contas sociais ou outros provedores. É usado em aplicações voltadas ao público (B2C/B2B).

## Conditional Access

Controla o acesso com base em condições (local, dispositivo, risco). Pode exigir MFA ou bloquear acessos suspeitos. Aumenta a segurança de forma inteligente e dinâmica.

## Defender for Cloud

O Microsoft Defender for Cloud é uma solução de segurança e proteção. Monitora recursos e identifica vulnerabilidades e ameaças. Fornece recomendações para melhorar a postura de segurança.
