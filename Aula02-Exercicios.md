# AULA 02 - GPT NO SEU TRABALHO: FLUXO E DADOS
[Aula 2](https://youtu.be/CFaCEnPzodU)

## Links, dicas e notas de aula

Boas-vindas à segunda aula da Imersão IA!

Ontem na primeira aula, demos nosso primeiro mergulho em inteligência artificial, e hoje continuaremos a falar sobre aplicações práticas do GPT. Neste mergulho, vamos nos aprofundar um pouco mais e mostrar como você pode aproveitar todo o potencial do ChatGPT para arquivos que são muito comuns no seu dia a dia, como planilhas, JSON e CSV.

Abaixo, disponibilizamos todo o material necessário para que você acompanhe a aula e avance em seu projeto.

- [Notion - Guia de Mergulho](https://www.notion.so/imersaoia/4d2f9f4e9b6d4d5795d5a4804092a1b3)
  - Para te ajudar durante as aulas, criamos um Notion exclusivo da Imersão IA! Com dicas de como se preparar para a Imersão, conteúdos relacionados ao tema, calendário para você ficar por dentro de tudo que vai rolar nessa edição e muito mais.

- [Discord da Imersão IA](https://discord.com/invite/P4aDhFprFv)
  - Nosso servidor no Discord será o ponto de encontro perfeito para você interagir com outros estudantes, tirar dúvidas e compartilhar suas descobertas. Você pode até mesmo utilizar uma ferramenta de Inteligência Artificial para gerar imagens e fazer perguntas. Entre agora mesmo no Discord da Imersão IA!

## Prompts da aula

Aqui você encontra os prompts iniciais da aula:

1. Resuma as críticas a seguir para o filme "Avatar". Para cada uma delas diga qual é o sentimento, se é positivo, negativo ou neutro.

2. Analise as críticas abaixo e me responda em português:
   - Quantos filmes estão sendo analisados?
   - Quais são os nomes de todos os filmes?
   - Um resumo curto de cada filme, baseado nas críticas.
   - Gere uma nota pra cada filme, baseado nas críticas.

3. Dada a avaliação do filme a seguir, qual nota de 0 a 10 você acha que o avaliador deu?

4. Tenho uma planilha de avaliações de filmes no Google Sheets, onde cada linha é uma avaliação. Na coluna A está o nome do filme e na coluna D está a nota do filme que pode estar em texto. Qual fórmula posso usar para agrupar os filmes com a média de suas notas?

## Links citados

- [Planilha com as críticas ao filme Avatar](https://docs.google.com/spreadsheets/d/1PGg7V1T9DXnylHyfLWg1TG-ITRmCZZNpRbInJ0BX6h4/edit#gid=0)

- [Arquivo JSON com 20 filmes e sem as notas](https://raw.githubusercontent.com/alura-cursos/imersao-dados-2-2021/main/dados/movie_metadata_without_scores.csv)

- [Arquivo JSON com 20 filmes e com as notas](https://raw.githubusercontent.com/alura-cursos/imersao-dados-2

-2021/main/dados/movie_metadata_with_scores.csv)

- [SheetGPT - Extensão para Google Spreadsheets](https://openai.com/blog/announcing-sheetgpt/)

- [Link da ferramenta ChatGPT.openai](https://platform.openai.com/docs/guides/chat)

- [Link para a ferramenta Stable Diffusion](https://platform.openai.com/docs/guides/stable-baselines)

## Desafios

1. Crie 10 críticas variadas para filmes.

2. Peça ao ChatGPT para gerar 10 críticas variadas para outro filme. Em seguida, solicite que ele converta essas respostas para o formato CSV, copie esses valores e salve-os em um arquivo de texto (.txt). Depois disso, abra o Google Sheets, crie uma nova planilha e importe o arquivo .txt (em "Arquivo" -> "Importar" -> "Fazer upload"). Ao fazer essa importação, pode ocorrer um erro se o Google Sheets confundir as vírgulas de separação com vírgulas presentes no texto. Caso ocorra algum erro, peça ao ChatGPT para corrigi-lo.

3. Sugira descrições de imagens para serem inseridas em outras IA's. Utilize o ChatGPT para sugerir descrições de imagens que possam ser inseridas em outras inteligências artificiais, como o Stable Diffusion. Peça ao ChatGPT para criar 5 descrições de imagens com estilos diferentes, a fim de explorar essa combinação entre o ChatGPT e o Stable Diffusion.

4. Calcule a média salarial de pessoas com o Google Sheets e o ChatGPT. Usando a função GPT_LIST() do SheetGPT, gere 20 nomes de pessoas brasileiras na coluna A, a área de atuação dessas pessoas (como "Marketing", "TI", "Direito" ou "Saúde") na coluna B e 20 valores aleatórios de salário entre 1.000 e 20.000 na coluna C. Agora, peça ao ChatGPT para criar uma macro para o Google Sheets que calcule a média desses salários e mostre a resposta na célula D2.

## Divulgue seu projeto

Mostre o seu projeto para o mundo compartilhando no LinkedIn e Instagram! Marque a Alura (@AluraOnline) e o Paulo (@paulo_hipster). Vamos adorar ver os seus projetos e acompanhar a sua evolução! Lembre-se de utilizar a hashtag #ImersaoIA para que o seu projeto alcance ainda mais pessoas.

Bom mergulho e até a próxima aula!