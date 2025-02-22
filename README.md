# Explorando os Recursos de IA Generativa com Copilot e OpenAI

![GitHub](https://img.shields.io/github/license/Paucinha/api-ecommerce-dio?style=flat-square)

Neste LAB, abordaremos o Copiloto e exploraremos os recursos da OpenAI, concentrando-nos tanto nos filtros de conteúdo quanto na criação. Durante a prática, examinaremos de perto as funcionalidades dessas ferramentas, ao final do LAB, teremos uma compreensão mais aprofundada e prática desses recursos oferecidos pela OpenAI.

**Inteligência Artificial (IA) | Azure Machine Learning**

**Full-Stack | Básico**

### Explore o Microsoft Copilot no Microsoft Edge

Bem-vindo ao mundo emocionante do Microsoft Copilot!

Neste exercício, você aproveitará o poder do Copilot para explorar uma nova ideia de negócio: abrir uma empresa de limpeza corporativa.

Imagine isso: você está prestes a lançar um serviço de limpeza de alto nível que revolucionará os espaços de escritório em todos os lugares. Com o Microsoft Copilot ao seu lado, você pesquisará tendências de mercado e desenvolverá um plano de negócios sólido. Mas isso não é tudo! Você também criará documentos atraentes, apresentações atraentes e e-mails persuasivos para ajudar a tirar sua ideia do papel e atrair investidores.

Prepare-se para liberar sua criatividade e perspicácia empresarial enquanto navega por este laboratório envolvente e interativo. Ao final deste exercício, você terá um conjunto abrangente de materiais que o colocarão no caminho para o sucesso empresarial. Vamos começar e tornar sua empresa de limpeza corporativa uma realidade!

 :exclamation: **Observação**: este exercício pressupõe que você tenha uma [conta pessoal da Microsoft](https://signup.live.com/) (como uma conta outlook.com) com a qual você está conectado ao [Microsoft Edge](https://www.microsoft.com/edge/download) no seu computador. Se você tiver uma conta de trabalho e uma conta pessoal, certifique-se de selecionar sua conta pessoal nas configurações de conta no canto superior esquerdo do Microsoft Edge.

### Use o Copilot para explorar um documento e pesquisar uma ideia

Para começar sua exploração da IA ​​generativa, vamos usar o Microsoft Copilot no Edge para examinar um documento existente e extrair alguns insights dele.

1. No Microsoft Edge, navegue até [o OneDrive](https://onedrive.live.com) e `https://onedrive.live.com` entre usando sua conta pessoal da Microsoft, fechando todas as mensagens de boas-vindas ou ofertas exibidas.

2. Em outra aba do navegador, abra o documento [Business Idea.docx](https://github.com/MicrosoftLearning/mslearn-ai-fundamentals/raw/main/data/generative-ai/Business%20Idea.docx) de `https://github.com/MicrosoftLearning/mslearn-ai-fundamentals/raw/main/data/generative-ai/Business%20Idea.docx`. Então, quando o documento abrir no Edge, selecione a opção **Editar uma cópia** para copiar o documento para o seu OneDrive. O documento deve então abrir no Microsoft Word online automaticamente.

:exclamation: **Dica**: Se você não vir a opção de editar uma cópia, baixe-a para seu computador local. Em seguida, no OneDrive, use o botão **+ Adicionar novo** para carregar o arquivo **Business Idea.docx** do seu computador local para o OneDrive.

3. Veja o texto no documento **Ideia de Negócio**, que descreve algumas ideias de alto nível para um negócio de limpeza na cidade de Nova York.

4. Use o ícone **do Copilot** na barra de ferramentas do Edge para abrir o painel do Copilot, conforme mostrado aqui:

![deia de Negócio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/generative-ai/edge-copilot.png}

## Explore Azure OpenAI

### Prepare-se para um projeto de desenvolvimento de IA

Neste exercício, você usa o portal do Azure AI Foundry para criar um hub e um projeto, prontos para uma equipe de desenvolvedores criar uma solução de IA.

#### Abra o portal do Azure AI Foundry

Vamos começar entrando no portal do Azure AI Foundry.

1. Em um navegador da Web, abra o [portal do Azure AI Foundry](https://ai.azure.com) em `https://ai.azure.come faça login usando suas credenciais do Azure`. Feche todas as dicas ou painéis de início rápido que forem abertos na primeira vez que você fizer login e, se necessário, use o logotipo **do Azure AI Foundry** no canto superior esquerdo para navegar até a página inicial, que se parece com a seguinte imagem:

![Azure AI Foundry](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/media/ai-foundry-home.png)

2. Revise as informações na página inicial.

#### Crie um hub e um projeto

Um *hub* de IA do Azure fornece um espaço de trabalho colaborativo dentro do qual você pode definir um ou mais *projetos*. Vamos criar um projeto e um hub de IA do Azure e revisar os recursos do Azure que são criados para dar suporte a eles.

1. Na página inicial, selecione **+ Criar projeto**.
2. No assistente **Criar um projeto**, insira um nome de projeto adequado para (por exemplo, `my-ai-project`) e revise os recursos do Azure que serão criados automaticamente para dar suporte ao seu projeto.
3. Selecione **Personalizar** e especifique as seguintes configurações para seu hub:

* **Nome do hub**: *Um nome exclusivo - por exemplo* `my-ai-hub`
* **Assinatura**: *Sua assinatura do Azure*
* **Grupo de recursos**: *crie um novo grupo de recursos com um nome exclusivo (por exemplo, `my-ai-resources`) ou selecione um existente*
* **Localização**: Selecione **Ajude-me a escolher** e, em seguida, selecione **gpt-4** na janela do auxiliar de localização e use a região recomendada*
* **Conecte o Azure AI Services ou o Azure OpenAI**: *crie um novo recurso do AI Services com um nome apropriado (por exemplo, `my-ai-services`) ou use um existente*
* **Conectar Azure AI Search**: Pular conexão

:exclamation: * Os recursos do Azure OpenAI são limitados no nível do locatário por cotas regionais. No caso de um limite de cota ser atingido posteriormente no exercício, há uma possibilidade de você precisar criar outro recurso em uma região diferente.

4. Selecione **Next** e revise sua configuração. Depois, selecione **Create** e aguarde a conclusão do processo.
5. Quando seu projeto for criado, feche todas as dicas exibidas e revise a página do projeto no portal do Azure AI Foundry, que deve ser semelhante à seguinte imagem:

![any text](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/media/ai-foundry-project.png)

6. Na parte inferior do painel de navegação à esquerda, selecione **Management center**. O management center é onde você pode configurar as definições nos níveis de *hub* e *projeto*; ambos mostrados no painel de navegação.

![any text](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/media/ai-foundry-management.png)

Observe que no painel de navegação, você pode visualizar e gerenciar ativos de nível de hub e projeto nas seguintes páginas:

* Visão geral
* Usuários
* Modelos e endpoints
* Recursos conectados
* Computação ( *somente nível de hub* )

:exclamation: **Observação**: dependendo das permissões atribuídas ao seu Entra ID no seu locatário do Azure, talvez você não consiga gerenciar recursos no nível do hub.

7. No painel de navegação, na seção do seu hub, selecione a página **Visão geral** para visualizar detalhes do seu hub.
8. No painel **Propriedades do Hub**, selecione o link para o grupo de recursos associado ao hub para abrir uma nova guia do navegador e navegar até o portal do Azure. Entre com suas credenciais do Azure, se solicitado.

9. Veja o grupo de recursos no portal do Azure para ver os recursos do Azure que foram criados para dar suporte ao seu hub e projeto.

![any text](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/media/azure-portal-resources.png)

Observe que os recursos foram criados na região que você selecionou ao criar o hub.









## Links Importantes

[Explore generative AI with Microsoft Copilot](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/12-generative-ai.html)

[Explore Azure OpenAI](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/13-azure-openai.html)

[Explore content filters in Azure OpenAI](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/06-Explore-content-filters.html)

##

Projeto desenvolvido durante o [**Bootcamp Bradesco - Java Cloud Native**](https://www.dio.me/bootcamp/bradesco-java-cloud-native), fornecido pela [**DIO**](https://www.dio.me/)

##

- [By Páucinha](https://github.com/Paucinha)
