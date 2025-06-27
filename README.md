# AzureIA
Prepare-se para um projeto de desenvolvimento de IA
Neste exercício, você usa o portal do Azure AI Foundry para criar um projeto, pronto para criar uma solução de IA.

Este exercício leva aproximadamente 30 minutos.

Observação: algumas das tecnologias usadas neste exercício estão em versão prévia ou em desenvolvimento ativo. Você pode experimentar algum comportamento inesperado, avisos ou erros.

Abra o portal do Azure AI Foundry
Vamos começar entrando no portal do Azure AI Foundry.

Em um navegador da Web, abra o portal do Azure AI Foundry em e entre usando suas credenciais do Azure. Feche todas as dicas ou painéis de início rápido abertos na primeira vez que você entrar e, se necessário, use o logotipo do Azure AI Foundry no canto superior esquerdo para navegar até a home page, que é semelhante à imagem a seguir (feche o painel Ajuda se estiver aberto):https://ai.azure.com

Captura de tela do portal do Azure AI Foundry.

Revise as informações na página inicial.

Criar um projeto
Um projeto de IA do Azure fornece um workspace colaborativo para desenvolvimento de IA. Vamos começar escolhendo um modelo com o qual queremos trabalhar e criando um projeto para usá-lo.

Observação: os projetos do AI Foundry podem ser baseados em um recurso do Azure AI Foundry, que fornece acesso a modelos de IA (incluindo o Azure OpenAI), serviços de IA do Azure e outros recursos para desenvolver agentes de IA e soluções de chat. Alternativamente, os projetos podem ser baseados em recursos de hub de IA; que incluem conexões com recursos do Azure para armazenamento seguro, computação e ferramentas especializadas. Os projetos baseados no Azure AI Foundry são ótimos para desenvolvedores que desejam gerenciar recursos para o desenvolvimento de aplicativos de chat ou agente de IA. Os projetos baseados em hub de IA são mais adequados para equipes de desenvolvimento empresarial que trabalham em soluções complexas de IA.

Na home page, na seção Explorar modelos e recursos, pesquise o modelo; que usaremos em nosso projeto.gpt-4o
Nos resultados da pesquisa, selecione o modelo gpt-4o para ver seus detalhes e, na parte superior da página do modelo, selecione Usar este modelo.
Quando solicitado a criar um projeto, insira um nome válido para o projeto e expanda Opções avançadas.
Selecione Personalizar e especifique as seguintes configurações para o seu projeto:
Recurso do Azure AI Foundry: um nome válido para o recurso do Azure AI Foundry
Assinatura: sua assinatura do Azure
Grupo de recursos: criar ou selecionar um grupo de recursos
Região: selecione qualquer local compatível com os serviços de IA*
* Alguns recursos de IA do Azure são restritos por cotas de modelo regional. No caso de um limite de cota ser excedido posteriormente no exercício, existe a possibilidade de você precisar criar outro recurso em uma região diferente.

Selecione Criar e aguarde a criação do projeto, incluindo a implantação do modelo gpt-4 selecionado.
Quando seu projeto for criado, o playground de bate-papo será aberto automaticamente para que você possa testar seu modelo:

Captura de tela de um playground de chat do projeto do Azure AI Foundry.

No painel de navegação à esquerda, selecione Visão geral para ver a página principal do seu projeto; que se parece com isso:

Observação: Se um erro de permissões insuficientes for exibido, use o botão Corrigi-me para resolvê-lo.

Screenshot of a Azure AI Foundry project overview page.

Na parte inferior do painel de navegação à esquerda, selecione Centro de gerenciamento. O centro de gerenciamento é onde você pode definir as configurações nos níveis de recurso e projeto; que são mostrados no painel de navegação.

Screenshot of the Management center page in Azure AI Foundry portal.

O nível de recurso está relacionado ao recurso Azure AI Foundry que foi criado para dar suporte ao seu projeto. Esse recurso inclui conexões com os Serviços de IA do Azure e os modelos do Azure AI Foundry; e fornece um local central para gerenciar o acesso do usuário a projetos de desenvolvimento de IA.

O nível do projeto está relacionado ao seu projeto individual, onde você pode adicionar e gerenciar recursos específicos do projeto.

No painel de navegação, na seção do recurso do Azure AI Foundry, selecione a página Visão geral para exibir seus detalhes.
Selecione o link para o grupo de recursos associado ao recurso para abrir uma nova guia do navegador e navegue até o portal do Azure. Entre com suas credenciais do Azure, se solicitado.
Exiba o grupo de recursos no portal do Azure para ver os recursos do Azure que foram criados para dar suporte ao recurso do Azure AI Foundry e ao seu projeto.

Screenshot of an Azure AI Foundry resource and project resources in the Azure portal.

Observe que os recursos foram criados na região selecionada ao criar o projeto.

Feche a guia do portal do Azure e retorne ao portal do Azure AI Foundry.
Examinar as conexões do projeto
Seu projeto do Azure AI Foundry e o recurso do Azure AI Foundry ao qual ele pertence incluem conexões com recursos que você pode usar em aplicativos de IA.

Na página Centro de gerenciamento, no painel de navegação, em seu projeto, selecione Ir para o recurso.
Na página Visão geral do projeto, exiba a seção Pontos de extremidade e chaves; que contém pontos de extremidade e chaves de autorização que você pode usar no código do aplicativo para acessar:
O projeto Azure AI Foundry e todos os modelos implantados nele.
Azure OpenAI em modelos do Azure AI Foundry.
Serviços de IA do Azure
Testar um modelo de IA generativa
Agora que você sabe algo sobre a configuração do seu projeto do Azure AI Foundry, pode retornar ao playground de chat para explorar o modelo implantado.

No painel de navegação à esquerda do seu projeto, selecione Playgrounds
Abra o playground do Chat e verifique se a implantação do modelo gpt-4o está selecionada na seção Implantação.
No painel Configuração, na caixa Fornecer instruções e contexto ao modelo, insira as seguintes instruções:

código
You are a history teacher who can answer questions about past events all around the world.
Aplique as alterações para atualizar a mensagem do sistema.
Na janela de chat, insira uma consulta como e exiba a resposta:What are the key events in the history of Scotland?

Screenshot of the playground in Azure AI Foundry portal.

Resumo
Neste exercício, você explorou o Azure AI Foundry e viu como criar e gerenciar projetos e seus recursos relacionados.

Arrumar
Se você terminou de explorar o portal do Azure AI Foundry, exclua os recursos criados neste exercício para evitar incorrer em custos desnecessários do Azure.

No portal do Azure em , exiba o conteúdo do grupo de recursos em que você implantou os recursos usados neste exercício.https://portal.azure.com
Na barra de ferramentas, selecione Excluir grupo de recursos.
Insira o nome do grupo de recursos e confirme que deseja excluí-lo.
