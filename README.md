# Explore a IA generativa com o Microsoft Copilot
Documentação criada para orientar no teste do Microsoft Copilot na geração de imagem usando o DALL-E, fazendo perguntas para gerar respostas e geração de código.

## Faça login no Microsoft Copilot

1. Abra o [Copilot](copilot.microsoft.com) e entre com sua conta pessoal da Microsoft.

2. O Microsoft Copilot usa IA generativa para aprimorar os resultados de pesquisa do Bing. O que isto significa é que, diferentemente da pesquisa apenas, que retorna conteúdo existente, o Microsoft Copilot pode reunir novas respostas com base na modelagem de linguagem natural e nas informações da web.

3. Na parte inferior da tela, você verá uma janela Pergunte-me qualquer coisa . À medida que você insere prompts na janela, o Copilot usa todo o thread da conversa para retornar respostas. Por exemplo, vamos tentar fazer uma série de perguntas sobre viagens.

![Captura de tela de 2024-03-16 10-41-10](https://github.com/dani-peixoto/lab-azure-copilot/assets/3649843/05e1119f-b794-407e-9087-de533ce0579e)

## Use prompts para gerar respostas

1. Digite um prompt: **Quais são os três pós e contrar de viajar no verão?** "Você verá Searching for:… e Generating…" aparecer antes da resposta. O modelo usa as respostas pesquisadas como informação de base para gerar respostas originais. Observe que o final da resposta contém links para suas fontes.

![prompt](https://github.com/dani-peixoto/lab-azure-copilot/assets/3649843/b01a8ef8-96e4-4786-859d-d26ddade4d5d)

2. Digite um prompt: **Informe mais 3 doces**. O que você quer dizer com esta mensagem é que gostaria de ver mais três motivos positivos para viajar no verão que ainda não foram listados. Observe que, com esse prompt, você está solicitando ao Copilot que faça duas coisas que a pesquisa por si só não faz: usar a resposta do chat anterior para excluir o que é retornado na nova resposta e usar o tópico do chat anterior sem declará-lo explicitamente.

3. Digite um prompt: **Quais são os três lugares onde posso ir para encontrar menos multidões?**

4. O botão **Novo tópico** próximo à janela de bate-papo é útil. Clicar nele limpa o tópico da conversa anterior para que as respostas do novo tópico não sejam baseadas no tópico anterior. Use o ícone Novo tópico próximo à janela de bate-papo para limpar seu histórico de mensagens.

![novo_tópico](https://github.com/dani-peixoto/lab-azure-copilot/assets/3649843/c170e7ad-34d0-4e46-a29d-fc490cdc5560)

## Experimente a geração de imagens

1. Agora vamos ver um exemplo de geração de imagens. Digite um prompt: **Crie a imagem de um elefante comendo um hambúrguer**. Observe que uma mensagem que "tentarei criar que…" aparece antes que o Copilot retorne uma resposta.

![Copilot](https://github.com/dani-peixoto/lab-azure-copilot/assets/3649843/d55bed94-7cb6-41d5-87bf-5c168b53190b)

> [!Important]
> É importante notar que a resposta pode parecer semelhante, mas não igual. Isso ocorre porque as respostas são variadas.

3. Na resposta, há um texto na parte inferior que diz **“Powered by DALL-E”**. Considere como o **DALL-E** é baseado em grandes modelos de linguagem, à medida que sua entrada de linguagem natural gera imagens.

4. Retorne ao chat do Copilot clicando no ícone do Microsoft Bing no canto superior direito da tela

## Experimente a geração de código

1. Agora vamos ver um exemplo de geração e tradução de código. Digite um prompt: **Use Javascript para criar uma lista**.

![javascript](https://github.com/dani-peixoto/lab-azure-copilot/assets/3649843/65d7a64b-60b9-4f2d-b213-43329dea84f8)

2. Digite no prompt: **Traduza isso para C#**. Observe como você não precisou especificar o que é “aquilo”, como o Copilot sabe para se referir ao histórico de conversas.

![C#](https://github.com/dani-peixoto/lab-azure-copilot/assets/3649843/4504236a-76f7-4c26-9757-05785732836e)






