# AZ104 - Administrador Azure - Treinamento 
Desafio - Gerenciando Maquinas Virtuais Azure
  
  Primeira dica: Sempre lembre de seguir a documentacao oficial da Microsoft:  
    https://learn.microsoft.com/pt-br/system-center/vmm/manage-azure-vms?view=sc-vmm-2022

  Defina o requiremento de negocio para verificar o melhor SKU de hardware (memoria, processamento, disco) que se a aplica a esta demanda. Se necessario, voce pode alterar o "resing" posteriormente.
  
  Escolhe como voce vai fazer a sua implantacao:
    1. Portal
    2. PowerShell    
    3. CLI

  A aplicacao da TAG para Maquina Virtual e importante para uma boa administracao de custo / utilizacao.

  Passos resumidos para criar a maquina virtual:
    1. Create a virtual Machine
      Coloque o nome (Nome usado para a maquina. Exemplo: AZ104-VM01-BR)
      Zona (Regiao que voce quer alocar a maquina)
      Rede (VNET)
      Selecione a imagem (Windows, Linux)
      Size (SKU da Maquina)
      Senha (Senha que voce ira utilizar como administrador)
      Selecione os discos (Tamanho bem como a performance do mesmo)
      Selecione IP publicos (se necessario)
      Adicione TAG
      Revisa e Crie a sua maquina

        Veja progresso da criacao da maquina.
        Depois da criacao, valide as configuracoes.
        Libere a maquina para uso.

Lembre-se de definir muito bem os requisitos de maquina que voce precisa, pois isso impacta no seu custo.


    

    
