# Step Functions

    Hoje aprendi sobre o AWS Step Functions, que é um serviço da Amazon Web Services (AWS) usado para orquestrar fluxos de trabalho. Ele permite criar fluxos de trabalho complexos, coordenando diferentes serviços da AWS de maneira visual e intuitiva. Isso ajuda a construir aplicações distribuídas, onde várias tarefas ou processos podem ser organizados e executados em sequência ou em paralelo.

# Projeto Template

    Vi que o Step Functions oferece templates de projeto para ajudar a começar rapidamente. Esses templates servem como um ponto de partida para criar fluxos de trabalho comuns, como processamento de dados ou automação de tarefas. Escolher um template apropriado economiza tempo e oferece uma estrutura inicial sólida, especialmente se estou apenas começando com a ferramenta.

# Workflow Studio & ASL

    Hoje também aprendi a usar o Workflow Studio, uma ferramenta visual dentro do Step Functions. Com ela, é possível arrastar e soltar componentes para criar fluxos de trabalho sem precisar escrever código imediatamente. Esse editor visual traduz as ações para Amazon States Language (ASL), que é a linguagem JSON usada pelo Step Functions para definir os estados e transições de um fluxo de trabalho. Isso me ajuda a entender como cada passo do workflow está interconectado.

# Hello World

    Para colocar tudo em prática, criei meu primeiro fluxo de trabalho "Hello World". Isso me ajudou a entender a estrutura básica de um workflow no Step Functions, onde defini um estado simples que apenas imprime uma mensagem e finaliza. Foi uma boa introdução à interface e aos fundamentos da orquestração de estados.

# Nível 1 de Configuração - Permissão de Perfil

    Em seguida, aprendi sobre o primeiro nível de configuração: as permissões de perfil. No Step Functions, assim como em outros serviços AWS, é crucial configurar permissões adequadas para que os recursos certos possam ser acessados pelo workflow. Isso é feito usando o IAM (Identity and Access Management), onde preciso definir quem pode iniciar e gerenciar fluxos de trabalho e quais serviços os workflows têm permissão para usar.

# Nível 2 de Configuração - Disponibilidade de Serviço

    No nível 2 de configuração, explorei a disponibilidade do serviço. O Step Functions é uma ferramenta altamente disponível e distribuída, mas é importante configurar adequadamente o ambiente em que o workflow será executado. Isso envolve selecionar a região AWS correta para garantir baixa latência e resiliência, além de considerar a replicação entre regiões para maior tolerância a falhas.

# Criando um Assistente de Delivery

    Por fim, apliquei tudo o que aprendi criando um assistente de delivery usando o Step Functions. Esse fluxo de trabalho simula o processo de gerenciamento de entregas, coordenando tarefas como a aceitação do pedido, preparação, rastreamento da entrega e confirmação final. O fluxo foi dividido em várias etapas, e cada uma delas foi configurada para lidar com falhas e retentativas, utilizando a lógica condicional e paralelismo que o Step Functions oferece. Essa prática foi essencial para consolidar meu entendimento de como orquestrar processos complexos de maneira eficiente.
