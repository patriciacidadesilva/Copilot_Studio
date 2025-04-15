# Databricks notebook source
# MAGIC %md
# MAGIC ## 🚀 Como Criar um Agente de Inteligência Artificial no Microsoft Copilot Studio.
# MAGIC
# MAGIC O Microsoft Copilot Studio permite que você crie **Agentes Inteligentes** (chatbots) para automatizar respostas, interações e processos com base em fluxos definidos. Estes agentes podem ser integrados em canais como sites, Microsoft Teams, e-mails e outros.
# MAGIC

# COMMAND ----------

# MAGIC %md
# MAGIC ---

# COMMAND ----------

# MAGIC %md
# MAGIC
# MAGIC ### 💡 ETAPAS 👇

# COMMAND ----------

# MAGIC %md
# MAGIC #### 📌 Etapas para Criar um Copiloto Personalizado
# MAGIC
# MAGIC O processo de criação de um agente no Microsoft Copilot Studio segue uma trilha intuitiva e guiada:
# MAGIC
# MAGIC #### 1️⃣ Start – Criar um copiloto
# MAGIC Você inicia o projeto em poucos minutos, escolhendo o nome do copiloto, a linguagem e seu objetivo principal.
# MAGIC
# MAGIC #### 2️⃣ Build – Projetar a conversa
# MAGIC Nesta fase, você:
# MAGIC - Conecta a **base de dados de conhecimento** (como arquivos, páginas da web ou bases do Dataverse).
# MAGIC - Define **tópicos e fluxos de diálogo** com base em regras e IA generativa.
# MAGIC - Pode integrar **plug-ins e conectores de dados**.
# MAGIC - Estende as capacidades usando o **Azure AI Studio**, se necessário.
# MAGIC
# MAGIC #### 3️⃣ Publish – Publicar em canais
# MAGIC Depois de projetado e testado, seu copiloto pode ser publicado em múltiplos canais:
# MAGIC - Microsoft Teams
# MAGIC - Sites
# MAGIC - Aplicativos e redes sociais
# MAGIC - Outras plataformas de atendimento
# MAGIC
# MAGIC #### 4️⃣ Manage – Controlar e melhorar
# MAGIC Após publicado, o copiloto entra em produção, e você pode:
# MAGIC - **Monitorar interações**
# MAGIC - **Melhorar os tópicos e respostas**
# MAGIC - Gerenciar com segurança e aplicar **níveis de controle empresarial**
# MAGIC
# MAGIC
# MAGIC

# COMMAND ----------

# MAGIC %md
# MAGIC #### 1️⃣ 1. Start – Criar um copiloto
# MAGIC
# MAGIC Você pode criar um copiloto e colocá-lo em funcionamento. O Copilot Studio é um produto **E2E SaaS (end-to-end)** fácil de usar, onde você define:
# MAGIC
# MAGIC - Nome do copiloto
# MAGIC - Linguagem principal
# MAGIC - Setores de atuação
# MAGIC - Recursos que deseja integrar
# MAGIC
# MAGIC Essa interface intuitiva acelera o início do projeto.
# MAGIC
# MAGIC
# MAGIC

# COMMAND ----------

# MAGIC %md
# MAGIC #### 📚 2. Adicionar conhecimento ao copiloto
# MAGIC
# MAGIC Depois de criar o agente, o próximo passo é conectá-lo a **fontes de conhecimento**. Isso permite que ele responda com base em dados reais e específicos da sua empresa ou domínio.
# MAGIC
# MAGIC Você pode:
# MAGIC
# MAGIC - Conectar sites públicos (como páginas de FAQ, documentações, blogs, etc.)
# MAGIC - Utilizar bases internas como:
# MAGIC   - SharePoint
# MAGIC   - OneDrive
# MAGIC   - Dataverse
# MAGIC   - Bancos de dados (SQL, Azure, etc.)
# MAGIC   - APIs com conectores prontos
# MAGIC
# MAGIC Isso garante que seu agente tenha **respostas relevantes e atualizadas**, sem depender apenas de regras fixas.
# MAGIC
# MAGIC
# MAGIC

# COMMAND ----------

# MAGIC %md
# MAGIC #### 🔄 3. Personalizar tópicos e ações
# MAGIC
# MAGIC O Copilot Studio permite criar **tópicos de conversa personalizados**, misturando:
# MAGIC
# MAGIC - **Respostas generativas com IA**
# MAGIC - **Tópicos baseados em regras** e caminhos lógicos
# MAGIC - **Ações automatizadas** como ler tabelas do SAP, acessar APIs ou executar fluxos no Power Automate
# MAGIC
# MAGIC Você pode conectar o copiloto a seus sistemas de back-end com **milhares de conectores prontos**, criando fluxos inteligentes que executam ações com base nas perguntas dos usuários.
# MAGIC
# MAGIC

# COMMAND ----------

# MAGIC %md
# MAGIC #### 🚀 4. Publicar e transmitir ao vivo
# MAGIC
# MAGIC Após definir a lógica da conversa e integrar suas fontes de dados, é hora de **publicar** seu copiloto.
# MAGIC
# MAGIC Com apenas um clique, ele pode ser implantado e disponibilizado em diversos canais:
# MAGIC
# MAGIC - **Microsoft Teams**
# MAGIC - **Sites personalizados ou demo**
# MAGIC - **Aplicativos móveis**
# MAGIC - **Slack, Skype, Telegram, Twilio**
# MAGIC - **Email, Line, GroupMe**
# MAGIC - **Customer Engagement Hubs** como Dynamics 365, Salesforce, Zendesk, entre outros
# MAGIC
# MAGIC Isso permite que seu copiloto atue onde os usuários realmente estão, seja internamente na empresa ou em canais de atendimento ao cliente.
# MAGIC

# COMMAND ----------

# MAGIC %md
# MAGIC ####  📈 5. Analisar e Melhorar
# MAGIC
# MAGIC Após o copiloto estar em produção, o Copilot Studio oferece uma área de **analytics detalhada** para monitoramento de desempenho.
# MAGIC
# MAGIC Você pode acompanhar:
# MAGIC
# MAGIC - **Total de usuários e sessões**
# MAGIC - **Taxa de engajamento** (% de interações relevantes)
# MAGIC - **Taxa de resolução** (quando o copiloto resolve o problema sem escalonamento)
# MAGIC - **Satisfação do usuário**
# MAGIC - **Tópicos que precisam ser melhorados**
# MAGIC
# MAGIC Esses insights ajudam a refinar as conversas, ajustar fluxos e garantir que o copiloto esteja sempre aprendendo e evoluindo.
# MAGIC

# COMMAND ----------

# MAGIC %md
# MAGIC #### 🛠️ 6. Ajuste fino para adicionar sofisticação
# MAGIC
# MAGIC Com base nos dados analisados, você pode:
# MAGIC
# MAGIC - Adicionar novos **tópicos personalizados**
# MAGIC - Criar **condições lógicas** específicas por tipo de usuário, horário, linguagem, etc.
# MAGIC - Usar **ações e conectores dinâmicos** para melhorar a performance
# MAGIC - Refinar o comportamento do copiloto com **testes A/B e ajustes pontuais**
# MAGIC
# MAGIC Essa fase é crucial para **garantir um desempenho contínuo e evolutivo**, transformando o agente básico em um copiloto avançado e alinhado ao seu negócio.
# MAGIC

# COMMAND ----------

# MAGIC %md
# MAGIC #### 🤖 7. Adicionar serviços e expandir as capacidades
# MAGIC
# MAGIC Para casos mais avançados, o Copilot Studio permite integração com serviços da Microsoft como:
# MAGIC
# MAGIC - **Azure AI Studio** (com modelos customizados e afinamento)
# MAGIC - **Serviços Cognitivos do Azure**
# MAGIC - **Bot Framework**
# MAGIC - Outras APIs e frameworks de inteligência conversacional
# MAGIC
# MAGIC Essas integrações permitem que você:
# MAGIC
# MAGIC - Aumente a **sofisticação das respostas**
# MAGIC - Inclua **modelos LLM personalizados**
# MAGIC - Crie **pipelines de IA sob medida** para seu negócio
# MAGIC
# MAGIC
# MAGIC

# COMMAND ----------

# MAGIC %md
# MAGIC ---

# COMMAND ----------

# MAGIC %md
# MAGIC
# MAGIC ### 💡 DEMONSTRAÇÃO DE COMO FAZER 👇 

# COMMAND ----------

# MAGIC %md
# MAGIC #### 🧾 1. Criando o Agente

# COMMAND ----------

# MAGIC %md
# MAGIC 🔹Acesse o Copilot Studio pelo link: [https://copilotstudio.microsoft.com/]
# MAGIC
# MAGIC 🔹 No início já vai aparecer uma caixa de texto em branco com o título: **Descreva seu agente para criá-lo**
# MAGIC     - Coloque dentro dessa caixa de texto o seguinte prompt de comando:
# MAGIC     *"Meu Copilot vai responder sobre o Site do Itaú."* 
# MAGIC
# MAGIC 🔹 O Copiloto vai sugerir algumas opções de nome para o seu agente. Exemplo: Sugiro o nome "Assistente Itaú". Você gostaria de confirmar este nome ou prefere outro?
# MAGIC     *"Eu respondi que podia confirmar o nome, mas você pode responder como preferir."*
# MAGIC
# MAGIC 🔹 O Copiloto vai sugerir funções que você gostaria que ele desempenhasse, como por exemplo: primeiro, vamos definir o que o agente deve fazer, ele pode fornecer informações sobre produtos e serviços do Itaú, ajudar com dúvidas sobre o site, ou orientar sobre como realizar transações online, essas funções vem declaradas no lado direito da tela. 
# MAGIC     *"Eu respondi que podia usar as funções que ele sugeriu que estariam ótimas, mas você pode definir detalhamente quais achar mais interessante."*
# MAGIC
# MAGIC 🔹 Logo após ele vai te questionar se quer incluir alguma fonte de dados.
# MAGIC     - No nosso caso passei o Site do Itaú: [https://www.itau.com.br/]
# MAGIC
# MAGIC 🔹 Depois de repassada as primeiras instruções clique no Botão Azul **(CRIAR)** - lado direito da tela
# MAGIC
# MAGIC     
# MAGIC

# COMMAND ----------

# MAGIC %md
# MAGIC #### 🧾 2. Fazendo os Testes

# COMMAND ----------

# MAGIC %md
# MAGIC 🔹Do lado direito da tela na aba: **Testar seu agente**, digite perguntas para verificar se a criação do copiloto foi efetuada com sucesso, como por exemplo: *Quais informações tem no Site do Itaú?*  
# MAGIC (Lembrando que aqui, quanto mais específica for a pergunta, mais assertiva será a resposta do modelo. Neste caso, foi feita uma pergunta genérica apenas para testar se o assistente estava funcionando).
# MAGIC
# MAGIC 🔹Logo após a execução do teste, você será capaz de verificar acima **7 abas com os seguintes temas**:
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC #### 🧠 1. Visão Geral do Agente
# MAGIC Esta tela mostra um resumo geral do agente criado.
# MAGIC
# MAGIC - **Nome do agente**: Nome personalizado dado ao agente (ex: *"Assistente Itaú"*).
# MAGIC - **Descrição**: Define a finalidade do agente, como por exemplo: *"fornecer informações sobre produtos e serviços do Itaú"*.
# MAGIC - **Instruções gerais**: Pontos orientativos para guiar a IA no tipo de assistência que deve oferecer.
# MAGIC - **Tópicos cadastrados**: Lista de temas prontos para interação com usuários (ex: *“Obrigado”*, *“Saudação”*).
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC #### 📚 2. Conhecimento  
# MAGIC Aqui você gerencia as **fontes de conhecimento** utilizadas pela IA.
# MAGIC
# MAGIC - **Sugestões**: Recomendações do sistema para ampliar ou ajustar as fontes.
# MAGIC - **Fontes cadastradas**: Exemplo — site público do Itaú (`https://www.itau.com.br`).
# MAGIC - **Métricas**: Mostra o uso das fontes (em %), taxa de erros e taxa de respostas — indicadores úteis para acompanhar a performance do agente.
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC #### 💬 3. Tópicos 
# MAGIC Configuração dos **tópicos e gatilhos** que a IA irá reconhecer e responder.
# MAGIC
# MAGIC - **Nome**: Nome do tópico (ex: *“Obrigado”*, *“Tchau”*).
# MAGIC - **Gatilho**: Palavras/frases que disparam o tópico.
# MAGIC - **Status**: Indica se está ativado para uso.
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC #### ⚡ 4. Ações 
# MAGIC Área destinada à criação de **ações personalizadas**, como:
# MAGIC
# MAGIC - Executar comandos externos,
# MAGIC - Acessar sistemas de terceiros,
# MAGIC - Retornar informações específicas.
# MAGIC
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC #### 📈 5. Atividade 
# MAGIC Exibe um **histórico de interações** entre usuários e a IA (quando habilitada).
# MAGIC
# MAGIC - Há um link para **ativar a IA generativa** e começar a exibir dados.
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC #### 🌐 6. Canais 
# MAGIC Define onde o agente será publicado e utilizado:
# MAGIC
# MAGIC - **Canais disponíveis**: Teams + Microsoft 365, Site personalizado, Facebook, Telegram, Email, entre outros.
# MAGIC - Alguns requerem **conectores premium**.
# MAGIC - Há também suporte para hubs como Salesforce, Genesys e ServiceNow.
# MAGIC
# MAGIC ---
# MAGIC

# COMMAND ----------

# MAGIC %md
# MAGIC #### 🧾 3. Adicionando Conhecimentos

# COMMAND ----------

# MAGIC %md
# MAGIC 🔹Agora vamos adicionar mais alguns conhecimentos ao assistente. Para isso, vá até a aba: **Visão Geral**.  
# MAGIC Na seção *Conhecimento*, clique em **+ Adicionar conhecimento** e selecione, por exemplo, **SharePoint**.
# MAGIC
# MAGIC 🔹No caso descrito, selecionei um arquivo PDF fornecido pelo próprio Itaú, com o conteúdo do Código de Ética e Conduta:  
# MAGIC [https://www.itau.com.br/download-file/v2/d/57561cbd-c456-4e6d-b0f8-97d739129930/2d527bf0-6643-a345-6df3-f95117ab9bc9?origin=1](https://www.itau.com.br/download-file/v2/d/57561cbd-c456-4e6d-b0f8-97d739129930/2d527bf0-6643-a345-6df3-f95117ab9bc9?origin=1)  
# MAGIC Esse arquivo foi adicionado dentro do meu SharePoint e, em seguida, clique no botão azul **Adicionar**.
# MAGIC
# MAGIC 🔹Após adicionar a fonte de conhecimento, você será redirecionado de volta à tela principal do agente.  
# MAGIC Agora, clique na aba à direita chamada **Testar seu agente**. Isso fará com que a aba de *Tópicos* reapareça.
# MAGIC
# MAGIC 🔹Para associar o novo conhecimento a um gatilho, clique na caixa chamada *Gatilho*.  
# MAGIC Use a setinha (<- ->) e selecione o tipo **Frases**.  
# MAGIC Inclua agora frases que remetam ao conteúdo que você adicionou, como por exemplo: **"Código de Ética e Conduta"**, **"conduta profissional"**, etc.  
# MAGIC Depois clique no botão azul **Salvar**.
# MAGIC
# MAGIC 🔹Pronto! Agora você já pode fazer novas perguntas ao seu assistente, que ele utilizará esse segundo conhecimento como base para responder de forma mais precisa.
# MAGIC

# COMMAND ----------

# MAGIC %md
# MAGIC
# MAGIC ### 💡 DICAS PARA MELHORAR SEU AGENTE NO COPILOT STUDIO 👇 

# COMMAND ----------

# MAGIC %md
# MAGIC ---
# MAGIC #### 🔺 Dica 0 – Entenda a Relação entre a Pergunta e o Conhecimento
# MAGIC
# MAGIC Antes de se preocupar com respostas, reflita sobre:
# MAGIC
# MAGIC **👉 O que o usuário pergunta?**  
# MAGIC **👉 Qual base de conhecimento o agente tem disponível?**
# MAGIC
# MAGIC > A qualidade das respostas do seu Copilot depende diretamente de **como a pergunta é feita** e **se a base de conhecimento cobre aquele tema**.
# MAGIC
# MAGIC 📌 Essa dica nos lembra que nem sempre o problema está na IA — muitas vezes o conteúdo da base está incompleto ou mal estruturado.
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC #### 🛠 Como melhorar?
# MAGIC
# MAGIC 🔹 Avalie **como o usuário pergunta** e treine o Copilot com diferentes variações.  
# MAGIC 🔹 Melhore os prompts e comandos usando **técnicas de Prompt Engineering**.  
# MAGIC 🔹 Adicione frases ao **gatilho de tópicos** com formas diferentes de abordar o mesmo assunto.
# MAGIC
# MAGIC > Exemplo: se o conhecimento trata sobre o "Código de Ética", configure o tópico com variações como:  
# MAGIC > - "Qual é o código de conduta?"  
# MAGIC > - "Onde encontro o código de ética do Itaú?"  
# MAGIC > - "Regras de comportamento interno"
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC 📌 Lembre-se: **perguntas genéricas** podem ajudar a testar o funcionamento do agente, mas para produção o ideal é treinar com **perguntas específicas e realistas**.
# MAGIC
# MAGIC ---
# MAGIC

# COMMAND ----------

# MAGIC %md
# MAGIC ---
# MAGIC
# MAGIC #### 📝 Dica 1 – Planejamento é tudo: **Rascunhe o seu Copilot**
# MAGIC
# MAGIC Antes de abrir o Copilot Studio e começar a montar seu agente, siga esses três passos fundamentais:
# MAGIC
# MAGIC #### ✅ 1. Rascunhe o seu Copilot  
# MAGIC Crie um esboço visual com os principais elementos do seu bot:
# MAGIC
# MAGIC - Nome do agente
# MAGIC - Objetivo do bot
# MAGIC - Público-alvo
# MAGIC - Tópicos esperados e tipos de perguntas
# MAGIC - Tipos de resposta (texto, link, ações, etc.)
# MAGIC
# MAGIC 📄 Você pode usar um modelo como o da imagem para organizar essas informações de forma prática.
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC #### ✅ 2. Pense no Usuário  
# MAGIC 🔍 Coloque-se no lugar do usuário final:
# MAGIC
# MAGIC - Quais problemas ele quer resolver?
# MAGIC - Como ele costuma fazer perguntas?
# MAGIC - Que linguagem ele usaria?
# MAGIC
# MAGIC 💡 Isso vai ajudar a definir **gatilhos realistas**, melhorar a compreensão da IA e oferecer uma experiência mais útil.
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC #### ✅ 3. Defina a principal fonte de conhecimento  
# MAGIC O Copilot precisa de **onde buscar as informações**. Escolha com clareza:
# MAGIC
# MAGIC - PDF institucional?
# MAGIC - Página pública?
# MAGIC - SharePoint?
# MAGIC - Base de dados interna?
# MAGIC
# MAGIC 🎯 O ideal é começar com **uma única fonte principal bem estruturada**. Isso facilita o teste e garante respostas consistentes.
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC 📌 **Resumo prático da Dica 1**:
# MAGIC
# MAGIC | Etapa                       | Objetivo                                                                 |
# MAGIC |----------------------------|--------------------------------------------------------------------------|
# MAGIC | Rascunhar                  | Estruturar visualmente antes de montar                                  |
# MAGIC | Pensar no usuário          | Garantir que a linguagem e navegação façam sentido para o público final |
# MAGIC | Definir fonte de conhecimento | Dar à IA uma base confiável para responder corretamente                  |
# MAGIC
# MAGIC ---
# MAGIC

# COMMAND ----------

# MAGIC %md
# MAGIC ---
# MAGIC
# MAGIC #### 📊 Dica 2 – Mapeamento e estrutura: prepare o terreno antes de criar
# MAGIC
# MAGIC #### ✅ Antes: Mapeie as Perguntas Frequentes dos Usuários
# MAGIC
# MAGIC Antes mesmo de abrir o Copilot Studio, reúna as perguntas que os usuários costumam fazer no dia a dia. Exemplos:
# MAGIC
# MAGIC - "Como emitir 2ª via do boleto?"
# MAGIC - "Onde vejo meu extrato?"
# MAGIC - "Como falar com um gerente?"
# MAGIC
# MAGIC 📌 Essa etapa ajuda a prever as interações mais comuns e evita lacunas no atendimento da IA.
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC #### ✅ Depois: Crie uma Matriz de Uso do Copilot
# MAGIC
# MAGIC Monte uma matriz simples (pode ser no Excel mesmo) com as seguintes colunas:
# MAGIC
# MAGIC | Entrada (o que o usuário pergunta) | Tópico/Gatilho ativado | Resposta esperada | Canal de atendimento | Observações |
# MAGIC |------------------------------------|--------------------------|--------------------|------------------------|-------------|
# MAGIC
# MAGIC 💡 Com essa matriz, você consegue:
# MAGIC - Planejar os fluxos de conversas
# MAGIC - Evitar sobreposição entre tópicos
# MAGIC - Alinhar expectativas de entrada e saída do bot
# MAGIC - Medir a eficácia das respostas entregues
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC 🎯 **Objetivo final:** Transformar um rascunho solto em **um plano estruturado e estratégico** para seu Copilot.
# MAGIC
# MAGIC > Assim, o agente se torna mais inteligente, mais eficiente e mais conectado com as reais necessidades do usuário.
# MAGIC
# MAGIC ---
# MAGIC

# COMMAND ----------

# MAGIC %md
# MAGIC ---
# MAGIC
# MAGIC #### 🌐 Dica 3 – Cadastre-se no Microsoft 365 Developer Program
# MAGIC
# MAGIC Se você deseja testar seu Copilot com mais liberdade, utilizar canais como o Teams ou criar integrações mais avançadas, é fundamental participar do programa de desenvolvedores da Microsoft.
# MAGIC
# MAGIC #### 📌 O que é o Microsoft 365 Developer Program?
# MAGIC
# MAGIC É um programa oficial da Microsoft que oferece **um ambiente gratuito e completo para desenvolvimento e testes**, incluindo:
# MAGIC
# MAGIC - Licença E5 do Microsoft 365
# MAGIC - Acesso ao Teams, SharePoint, Outlook, entre outros
# MAGIC - Simulação de ambientes corporativos reais
# MAGIC - Ideal para **testes com IA, bots e automações**
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC #### ✅ Como participar?
# MAGIC
# MAGIC 1. Acesse o link:  
# MAGIC 🔗 [https://developer.microsoft.com/en-us/microsoft-365/dev-program](https://developer.microsoft.com/en-us/microsoft-365/dev-program)
# MAGIC 2. Clique em **Join now** (Inscreva-se agora).
# MAGIC 3. Complete seu perfil com dados profissionais ou acadêmicos.
# MAGIC 4. Escolha a opção de **ambiente instantâneo (Instant Sandbox)** para começar rapidamente.
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC #### 💡 Por que isso importa?
# MAGIC
# MAGIC ➡️ Com o ambiente de desenvolvedor, você pode:
# MAGIC
# MAGIC - **Testar Copilots reais no Teams**  
# MAGIC - Integrar dados do Microsoft 365 (como arquivos, agendas e e-mails)  
# MAGIC - Simular cenários empresariais sem afetar o ambiente da sua empresa
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC 🎯 **Resumo da Dica 3**:  
# MAGIC O Developer Program é seu “campo de testes oficial” para validar e demonstrar soluções com IA no ecossistema Microsoft, sem depender do ambiente produtivo da empresa.
# MAGIC
# MAGIC ---
# MAGIC

# COMMAND ----------

# MAGIC %md
# MAGIC ---
# MAGIC
# MAGIC #### 📚 Dica 4 – Estude com a trilha oficial da Microsoft
# MAGIC
# MAGIC Se você quer aprofundar seus conhecimentos no Copilot Studio, a própria Microsoft disponibiliza uma **trilha de aprendizado gratuita** e muito completa.
# MAGIC
# MAGIC #### 👨‍🏫 Curso: Criar copilots com o Microsoft Copilot Studio
# MAGIC
# MAGIC 📌 O que você vai aprender nessa trilha:
# MAGIC - Fundamentos sobre criação de agentes com IA
# MAGIC - Como definir tópicos e variáveis personalizadas
# MAGIC - Uso de entidades para estruturar fluxos
# MAGIC - Captura e extração de informações em tempo real
# MAGIC
# MAGIC 💡 A trilha é composta por módulos interativos e práticas guiadas — ideal tanto para iniciantes quanto para quem já conhece a ferramenta e quer se especializar.
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC #### 🔗 Acesse a trilha aqui:
# MAGIC [https://learn.microsoft.com/pt-br/training/paths/work-power-virtual-agents/](https://learn.microsoft.com/pt-br/training/paths/work-power-virtual-agents/)
# MAGIC
# MAGIC ⏱️ Duração estimada: 4h52min  
# MAGIC 🏅 XP: 5800 pontos
# MAGIC
# MAGIC ---
# MAGIC
# MAGIC 🎯 **Dica final da Dica 4**:  
# MAGIC Se você está começando do zero ou quer montar um Copilot profissional, siga essa trilha. É conteúdo oficial, atualizado e com exemplos práticos.
# MAGIC
# MAGIC ---
# MAGIC
