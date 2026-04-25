# Implementação de SIEM e Detecção de Ameaças com Wazuh

## Descrição do Lab
Este projeto demonstra a configuração e operação do Wazuh SIEM para monitoramento de segurança em tempo real. O foco principal foi a detecção de ataques de força bruta (Brute Force) e a análise de logs de eventos críticos em ambientes híbridos (Windows/Linux).

## Riscos Mitigados
* **Acesso Não Autorizado:** Detecção de múltiplas falhas de login.
* **Movimentação Lateral:** Monitoramento de escalada de privilégios.
* **Exposição de Serviços:** Identificação de varreduras de rede externas.

## Configurações Implementadas
* **Custom Rules:** Criação de regras personalizadas para alertas de alta severidade (Level 10+).
* **Agent Deployment:** Instalação e configuração de agentes em endpoints Windows Server e Ubuntu.
* **Integrity Monitoring:** Configuração do módulo FIM (File Integrity Monitoring) para diretórios sensíveis.

## Ferramentas Utilizadas
* Wazuh Manager & Dashboard
* Ubuntu Server (Log Collector)
* Windows Event Viewer Integration

## Resultados
* Redução no tempo de resposta a incidentes (MTTR) através de alertas via dashboard.
* Visualização clara de tentativas de intrusão por geolocalização de IP.