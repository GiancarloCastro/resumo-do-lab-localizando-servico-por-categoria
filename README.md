# Lab Microsoft Azure - Localizando Serviços por Categoria

Aprendi que os serviços do Azure são organizados em categorias e subdivisões para facilitar a localização. Por exemplo, dentro de `Análise`, o tópico `Processamento de Big Data` inclui Analysis Services, HDInsight, Data Factories e Data Lake Analytics.

## SLA e Alta Disponibilidade

O SLA (Service Level Agreement) define a disponibilidade do serviço. Exemplos:
- **99%:** até 7,2h de inatividade/mês
- **99,9%:** até 43,6min de inatividade/mês

A configuração de redundância aumenta a disponibilidade, impactando nos custos.

## Criação de Máquina Virtual

O painel de criação da VM permite configurar:
- Reinício automático
- Monitoramento
- Discos
- Redundância
- Autenticação

## Data Centers - Globo

No site [datacenters.microsoft.com/globe/explore](https://datacenters.microsoft.com/globe/explore), é possível visualizar os data centers e infraestrutura global do Azure.

## Armazenamento

A conta de armazenamento requer um nome único e uma região. Configurações incluem:
- **Desempenho:** `Standard` ou `Premium`
- **Redundância:** LRS, GRS, ZRS ou GZRS
- **Tipo:** Frio ou quente

### Recursos de Armazenamento
- **Containers:** gerenciamento de pastas/backups
- **Arquivos:** conexão SMB para Windows, Linux e Mac
- **Filas:** configuração de mensageria
- **Tabelas:** criação de tabelas

### Migração de Dados
- **AZ Copy:** ferramenta de transferência
- **Azure Data Box:** discos para migração de grandes volumes
- **Gerenciador de Armazenamento do Azure:** ferramenta para visualizar assinaturas e contas de armazenamento

## Identidade e Segurança (ENTRA ID)

Gerencia usuários e permissões no Azure. Permite:
- Criação e convite de usuários externos
- Sincronização com o ambiente on-premises via Entra Connect
- Recuperação de contas deletadas em até 30 dias

### Defender for Cloud
Ferramenta para segurança do ambiente, fornecendo recomendações de conformidade.

## Cálculo de Custos
- **Estimativa de Preços:** planejamento financeiro
- **TCO (Total Cost Ownership):** calcula economia da migração para o Azure

## Governança e Segurança
- **Portal de Confiança do Serviço:** normas de auditoria e conformidade
- **Purview:** governança de dados
- **Bloqueio de recursos**

## Ferramentas de Implantação
- **Cloud Shell:** execução de comandos PowerShell/Bash
- **Bicep:** automação de criação de VMs
- **Azure Arc:** gerenciamento de máquinas externas ao Azure

## Monitoramento
- **Azure Monitor:** insights e análises da infraestrutura
- **Service Health:** informações sobre manutenção e status dos serviços
- **Advisor:** recomendações para otimização da infraestrutura

