# Resumo-lab---IA-900-Dimensionamentos-em-M-quinas-Virtuais-na-Azure
Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure
 

Passo a Passo de Criação e Gerenciamento de Máquinas Virtuais no Azure

Durante o desenvolvimento do lab na DIO, aprendi a importância de configurar corretamente uma máquina virtual no Azure para evitar problemas futuros e garantir a eficiência do uso dos recursos. Abaixo está um resumo das lições aprendidas:

1-Exclusão do SSD ao Deletar a Máquina Virtual:
Ao excluir uma VM, é essencial lembrar de marcar a opção para excluir o SSD (disco de armazenamento). Se isso não for feito, o disco permanecerá vinculado, consumindo recursos e custos desnecessários.

2-Desligamento Automático:
Configure o desligamento automático da VM para economizar custos quando não estiver em uso. No entanto, lembre-se que essa opção não liga a máquina automaticamente, então é preciso ativá-la manualmente se necessário.

3-Exclusão da NIC e IP Público:
Ao excluir a VM, marque também a opção para excluir a placa de rede (NIC) e o IP público. Se esquecermos de fazer isso, essas peças podem continuar consumindo recursos e gerar cobranças desnecessárias.

4-Uso do Entrar ID (Azure Active Directory):
Ao fazer login, utilize o Entrar ID, o que facilita o gerenciamento seguro de acessos e autenticações no Azure, especialmente quando se trabalha com equipes.

5-Notificações de Desligamento:
Habilite as notificações de desligamento para que você seja avisado quando uma VM estiver prestes a ser desligada automaticamente, permitindo tomar ações caso necessário.

6-Habilitar Backup:
Para garantir a integridade dos dados e segurança das operações, habilite o backup da VM. Isso é crucial para evitar perda de dados importantes em caso de falhas ou exclusões acidentais.

7-Escolha da Máquina e Família Correta:
A escolha da família e tipo de máquina virtual deve ser feita com base no modelo de negócio ou nas necessidades do sistema. Escolher o tamanho e performance adequados garante uma operação mais eficiente e econômica.

8-Instalação de Extensões, como Antivírus:
Durante a configuração da VM, é possível instalar extensões como antivírus para aumentar a segurança do ambiente, ajudando na proteção contra ameaças.

Esses pontos me ajudaram a entender melhor o processo de criação e gerenciamento de VMs no Azure, permitindo que eu otimize o uso de recursos, economize custos e melhore a segurança do ambiente de TI.
