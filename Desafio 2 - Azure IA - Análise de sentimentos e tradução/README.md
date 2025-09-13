# Bootcamp Análise de Dados Randstad + Dio

💻 Descrição sobre o segundo projeto feito no Bootcamp, consistente na prática e aprofundamento nas ferramentas Azure Speech Studio e Language Studio - desenvolvendo soluções práticas em inteligência artificial para voz e linguagem.

## 📚 Da descrição do projeto

De início, esse foi o desafio proposto:

[Desafio](imagens/1%20-%20Instruções%20do%20desafio.png)

Assim sendo, temos dois principais desafios:

- A utilização do Microsoft Azure AI Speech para transcrever um áudio e,
- A análise de sentimentos de linguagem via Azure Language Studio.

Desta forma, a partir dessas instruções, visitei inicialmente a [documentação](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html) da Microsoft Azure Speech AI Foundry portal baixar o arquivo de teste e subi-lo ao website, como se vê neste [link](https://ai.azure.com/explore/models/aiservices/Azure-AI-Speech/version/1/registry/azureml-cogsvc/tryout?NewUX=true&Trigger=AutoRedirect_NoSpeechResources#realtime):

[Transcrição](imagens/2%20-%20Azure%20AI%20Foundry%20-%20transcrição.png)

Como se vê, o Microsoft Azure conseguiu transcrever o texto contido no áudio "WhatIACanDo.m4a" - que resultou no seguinte fragmento de texto (traduzido): "A IA nos permite construir softwares incríveis que podem melhorar a saúde, permitir que as pessoas superem desvantagens físicas, potencializar infraestruturas inteligentes, criar experiências de entretenimento incríveis e até salvar o planeta."

A transcrição, de acordo com a definição contida no [website](https://www.notta.ai/pt/audio-to-text) da Notta.ai, "[...] A transcrição de voz não faz parte das LLMs, mas as tecnologias de reconhecimento de fala e inteligência artificial utilizadas em plataformas de transcrição automática, como Notta e TurboScribe, são baseadas em algoritmos de aprendizado de máquina que podem identificar palavras faladas, pontuação e até mesmo diferentes idiomas. [...]"

Ou seja: neste caso, podemos verificar que há evidente influência da Inteligência Artificial para a materialização da transcrição de áudio, tal como vimos no caso acima. A transcrição de áudio pode ser útil na elaboração de legendas de conteúdos ou mesmo nas legendas de reuniões comporativas, tendo inegável utilidade nos dias atuais.

Prosseguindo, visitei a [documentação](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html) do Microsoft Azure Language Studio para obter os textos de exemplo e assim, conseguirmos analisar como ocorre a [análise de sentimentos de linguagem](https://language.cognitive.azure.com/tryout/sentiment):

[Prompt](imagens/3%20-%20Prompt%20-%20curto.png)

Neste prompt, foi considerada a seguinte frase de exemplo: "[...] I bought a size S and it fit perfectly. I found the zipper a little bit difficult to get up & down due to the side rushing. The color and material are beautiful in person. Amazingly comfortable! [...]"

E esse foi o resultado:

[Resultado](imagens/4%20-%20Resultado%20-%20curto.png)

O resultado de análise de sentimentos foi, portanto: 74% da linguagem foi positiva, 1% neutra e 25% negativa. Neste exemplo prático, temos a análise da compra de uma camiseta - em que o consumidor adquiriu uma camiseta no tamanho pequeno, mas serviu perfeitamente; o ziper era um pouco difícil de fechar, mas a cor e o tecido eram incríveis pessoalmente e ainda por cima, a camiseta era confortável.

O próprio sistema analisa o contexto geral (como visto acima), mas também verifica frase por frase - como exemplo:

[Frase 2](imagens/5%20-%20frase%20dois%20-%20curto.png)

Não é exagero dizer que essa análise é fundamental para ditar, por exemplo, o mercado consumidor: segundo dito pelo [Google Trends](https://trends.google.com.br/trends/), "[...] A pesquisa "Decisão Local 2025" revela que 96% dos consumidores no Brasil leem avaliações de outros clientes antes de escolher uma loja física. Isso inclui restaurantes, onde as avaliações no Google influenciam diretamente na opinião dos consumidores.[...]"

Definitivamente, ambas as funcionalidades têm crescente utilidade nos dias atuais e assumem cada vez mais importância nos contextos diários e corporativos.

## 🛠 Ferramentas utilizadas

- Microsoft Azure - Azure AI Speech e Language Studio.

## 💻 Autor / Contato

[@ricardo-otero12](https://github.com/ricardo-otero12)

Procure-me no LinkedIn: [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ricardogarcia56/)

