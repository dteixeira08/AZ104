# AZ104 - Administrador Azure - Treinamento 

    🚀 Desafio: Gerenciando Máquinas Virtuais na Azure

📌 Primeira Dica
  Sempre siga a documentação oficial da Microsoft para garantir boas práticas e atualizações constantes.
    https://learn.microsoft.com/pt-br/system-center/vmm/manage-azure-vms?view=sc-vmm-2022

🧠 Planejamento Inicial
  Defina os requisitos de negócio: Avalie memória, CPU, armazenamento e rede necessários para a carga de trabalho.
  Escolha o SKU ideal: Use a ferramenta de seleção de VMs para comparar tamanhos e preços.
  Considere escalabilidade: Planeje para possíveis aumentos (Scale Up) ou reduções (Scale Down) de recursos conforme sazonalidade ou demanda.

🛠️ Métodos de Implantação
  Escolha como deseja criar sua VM:
  Portal Azure – Interface gráfica, ideal para iniciantes.
  PowerShell – Automação e scripts avançados.
  Azure CLI – Flexível e multiplataforma.

🏷️ Uso de TAGs
  Aplicar TAGs é essencial para:
  Gerenciamento de custos
  Organização por ambiente (produção, teste, desenvolvimento)
  Relatórios e auditoria

📋 Passo a Passo para Criar uma Máquina Virtual
  Criar a VM:
    Nome: Ex. AZ104-VM01-BR
    Região: Escolha a zona geográfica
    Rede: Selecione ou crie uma VNET
    Imagem: Windows ou Linux
    Tamanho: Escolha o SKU adequado
    Autenticação: Defina usuário e senha
    Discos: Configure tipo e desempenho
    IP público: Adicione se necessário
    TAGs: Aplique conforme sua política
    Availability Set: Selecione o grupo 
    Revisar e Criar:
    Verifique todas as configurações
    Clique em “Criar” e acompanhe o progresso
    
    Pós-criação:
    Validar configurações
    Atualizar documentação interna
    Liberar a VM para uso
    
📈 Escalabilidade Inteligente
    Configure regras de escalonamento automático:
    Scale Up: Aumentar recursos em períodos críticos (ex: fechamento de mês)
    Scale Down: Reduzir recursos em períodos de baixa demanda
    
  Exemplos:
      Black Friday
      Campanhas promocionais
      Processos contábeis mensais

    🧱 Configuração de Availability Set
  Para garantir alta disponibilidade (SLA de 99,95%), crie um Availability Set antes de provisionar suas VMs:
  O que é: 
    Agrupamento lógico de VMs distribuídas entre diferentes domínios de falha e atualização.
  Benefícios:
    Minimiza impacto de falhas físicas (energia, rede)
    Evita reinício simultâneo durante manutenção
    Importante: VMs só podem ser adicionadas a um Availability Set no momento da criação.
  
  Como configurar:
    Crie o Availability Set no portal ou via CLI/PowerShell
    Ao criar a VM, selecione o Availability Set desejado
    Use discos gerenciados para maior confiabilidade

Caso prefira, tambem estou adicionando um checklist (que sempre nos ajuda no dia-a-dia) para facilitar a criacao e entendimento:

✅ Checklist: Criação de Máquinas Virtuais na Azure
🔍 Planejamento
  [ ] Requisitos de negócio definidos (memória, CPU, disco)
  [ ] SKU de máquina escolhido
  [ ] Necessidade de escalabilidade analisada (Scale Up/Down)
  [ ] TAGs definidas para gestão de recursos
🛠️ Escolha da Ferramenta de Implantação
  [ ] Portal Azure
  [ ] PowerShell
  [ ] Azure CLI
🧱 Infraestrutura
  [ ] Rede (VNET/Subnet) criada ou selecionada
  [ ] Availability Set criado (se for VM crítica)
  [ ] Grupos de Segurança configurados (NSG)
📦 Configurações da Máquina Virtual
  [ ] Nome (ex: AZ104-VM01-BR)
  [ ] Região/Zona de disponibilidade selecionada
  [ ] Imagem do SO selecionada (Windows/Linux)
  [ ] Tamanho/SKU definido
  [ ] Usuário e senha configurados
  [ ] Discos: tipo, tamanho e performance definidos
  [ ] IP Público necessário?
  [ ] Selecionado o Availability Set (caso aplicável)
  [ ] TAGs adicionadas
🚀 Implantação
  [ ] Configurações revisadas
  [ ] Máquina criada
  [ ] Progresso de implantação acompanhado
🔧 Pós-Criação
  [ ] Configurações validadas
  [ ] Documentação do ambiente atualizada
  [ ] Máquina liberada para uso
📈 Escalabilidade Inteligente (opcional)
  [ ] Regras de Scale Up/Down configuradas (ex: Fechamento de mês / Black Friday)

  Bons estudos. A documentacao sempre sera atualizada e melhorada. 
Feedback sao sempre bem-vindos.
