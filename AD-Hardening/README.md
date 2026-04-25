# Auditoria de Segurança e Hardening de Active Directory (AD)

## Descrição do Lab
Scripts e documentação voltados para a auditoria de identidades e reforço de segurança (Hardening) em ambientes de domínio Microsoft. O projeto simula a gestão de acessos em uma infraestrutura corporativa, aplicando o Princípio do Menor Privilégio.

## Objetivos Técnicos
* **Identificação de Vulnerabilidades:** Localização de contas inativas, senhas expiradas e usuários com privilégios excessivos.
* **Automação de Auditoria:** Scripts em PowerShell para geração de relatórios de conformidade.
* **GPO Hardening:** Implementação de políticas de grupo para desativação de protocolos legados (SMBv1, LLMNR).

## Conteúdo do Repositório
* `Audit-Users.ps1`: Script para exportar relatórios de contas órfãs.
* `GPO-Baselines.md`: Documentação das políticas de segurança aplicadas.

## Competências Demonstradas
* Administração de Windows Server.
* Governança de Identidade e Acesso (IAM).
* Segurança de Infraestrutura.