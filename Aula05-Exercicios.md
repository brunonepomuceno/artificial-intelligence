# AULA 05 - FLUXO DE TRABALHO: AUTOMAÇÃO NOCODE
[Aula 5]()
[![Aula 5](https://i9.ytimg.com/vi/O9sEBaoveAU/mqdefault.jpg?sqp=CPCw6KQG-oaymwEmCMACELQB8quKqQMa8AEB-AH-CYAC0AWKAgwIABABGBsgMih_MA8=&rs=AOn4CLBLtWH9IWASLUktwJr_3zxABRxihQ)](https://youtu.be/O9sEBaoveAU)

**Links, dicas e notas de aula**

Boas-vindas à quinta aula da Imersão IA!

Chegou a hora de mergulhar no conceito de "No-code"! Vamos usar uma ferramenta em que você não precisa conhecer nenhuma linha de código, o Zapier. No Zapier é possível criar automações incríveis com diversas plataformas, do Gmail ao Twitter, do Google Sheets ao Instagram. Nele vamos criar uma automação para responder e-mails de forma automática, aproveitando todo o potencial do GPT. Prepare-se para descobrir como essa poderosa combinação de ferramentas pode transformar o seu trabalho!

Ps: para encerrar a Imersão IA com chave de ouro, reservamos uma surpresa especial pra você mergulhar mais fundo em inteligência artificial e tecnologia! Fique de olho no seu e-mail, em breve você vai receber informações importantes!

Abaixo, disponibilizamos todo o material necessário para que você acompanhe a aula e avance em seu projeto.

- **Notion - Guia de Mergulho**
  Para te ajudar durante as aulas, criamos um Notion exclusivo da Imersão IA! Com dicas de como se preparar para a Imersão, conteúdos relacionados ao tema, calendário para você ficar por dentro de tudo que vai rolar nessa edição e muito mais.

- **Discord da Imersão IA**
  Nosso servidor no Discord será o ponto de encontro perfeito para você interagir com outros estudantes, tirar dúvidas e compartilhar suas descobertas. Você pode até mesmo utilizar uma ferramenta de Inteligência Artificial para gerar imagens e fazer perguntas.

  Entre agora mesmo no [Discord da Imersão IA!](https://discord.com/)

**Links citados na aula**
- Link da ferramenta: [ChatGPT](https://chat.openai.com/)
- Link para o [TechGuide](https://openai.com/research/tech-guide/)
- Link para a ferramenta: [Zapier](https://zapier.com/)
- Link para a plataforma da [OpenAI](https://openai.com/)
- Link para a ferramenta: [IFTTT](https://ifttt.com/)
- Link para a ferramenta: [Whisper](https://whisper.openai.com/)
- Link para a ferramenta: [ElevenLabs](https://eleven-labs.com/)
- Link para a ferramenta: [PDF.co](https://pdf.co/)
- Código para chamada de API usando o Google Colab

**Desafios do dia:**

1. Automação de categorização de tweets em uma planilha do Google Sheets

   Neste desafio, você deve criar um sistema automatizado para categorizar tweets em uma planilha do Google Sheets. A ideia é analisar campanhas de marketing nas redes sociais, especificamente aqueles que utilizam uma hashtag específica.

   Sempre que alguém postar um tweet com essa hashtag no Twitter, o sistema deve adicionar automaticamente o tweet a uma planilha do Google Sheets e categorizá-lo como "Positivo", "Negativo" ou "Neutro". Isso permitirá a análise da recepção da campanha e a possibilidade de aprimorar a estratégia de marketing.

  

 Você irá criar uma planilha no Google Sheets similar a esta, com as colunas "Usuário", "Tweet" e "Categoria". Depois, irá criar um novo Zap no Zapier, usando o Twitter como trigger (gatilho), e escolhendo a opção de busca por termo, utilizando a hashtag específica da campanha, como por exemplo #7DaysOfCode ou #ImersaoIA.

   Feito isso, você poderá adicionar mais uma ação, que será usar o ChatGPT para categorizar o tweet como "Positivo", "Negativo" ou "Neutro". Por fim, você terá outra ação, que será para adicionar as informações do tweet na planilha do Google Sheets que você já criou (pode escolher a opção de criar múltiplas linhas na planilha), e você irá mapear cada coluna para seu item correspondente, que virão ou do Twitter ou do ChatGPT.

2. Análise automática de currículos

   Você possui uma pasta no Dropbox onde os candidatos enviam seus currículos em formato PDF. Seu desafio é criar um fluxo automatizado que extraia os dados relevantes desses currículos e faça uma análise para determinar o nível de experiência de cada candidato.

   Para isso, primeiramente você irá criar uma conta gratuita no PDF.co para acessar os dados de um PDF e converter arquivos PDF em texto, e obterá sua API KEY.

   Em seguida, crie uma planilha no Google Drive similar a esta, com as colunas: "Nome completo", "Email", "Telefone", "Nível" e "Análise".

   Com isso pronto, você irá começar um novo Zap no Zapier, e o trigger será a adição de um arquivo PDF a uma pasta sua no Dropbox. No app da PDF.co, configure o evento "PDF to Anything Converter" e insira sua API KEY. Defina o formato de saída como "Plain text without layout...". Preencha o campo "Source PDF URL" com o "1. Share link" do arquivo PDF no Dropbox. Selecione o idioma como "Portuguese".

   Agora sim, você vai brincar com o ChatGPT. Você pode adicionar várias ações dele uma depois da outra. Cada ação irá extrair dados diferentes do texto do currículo:

   - Na primeira ação, extraia apenas o nome completo do candidato.
   - Na segunda ação, extraia apenas o email do candidato.
   - Na terceira ação, extraia apenas o telefone do candidato.
   - Na quarta ação, faça a análise do currículo. Avalie anos de experiência, projetos relevantes e tecnologias com as quais o candidato trabalhou. Classifique o nível do candidato como Júnior, Pleno ou Sênior.
   - Na quinta e última ação, analise a resposta anterior do ChatGPT e responda com uma palavra se o candidato é Júnior, Pleno ou Sênior.

   Por fim, insira os dados extraídos na planilha criada usando uma ação do Google Sheets no Zapier (pode escolher a opção de criar múltiplas linhas na planilha).

**Divulgue o seu projeto!**

Mostre o seu projeto para o mundo compartilhando no LinkedIn e Instagram! Marque a Alura (@AluraOnline) e o Paulo (@paulo_h

ipster). Vamos adorar ver os seus projetos e acompanhar a sua evolução! Lembre-se de utilizar a hashtag #ImersaoIA para que o seu projeto alcance ainda mais pessoas.

Bom mergulho e até a próxima aula!