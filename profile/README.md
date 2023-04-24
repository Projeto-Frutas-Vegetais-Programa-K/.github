# Auxílio na tomada de decisão no processo de compra de frutas e vegetais

Seja bem-vindo ao GitHub do nosso projeto, concebido no Programa K! 

Nestes [repositórios](https://github.com/orgs/Projeto-Frutas-Vegetais-Programa-K/repositories), vamos te apresentar nossa ideia e a(s) maneira(s) como ela foi abordada.

Se tiver quaisquer dúvidas ou curiosidades, não hesite em entrar em [contato](https://github.com/Projeto-Frutas-Vegetais-Programa-K/.github/blob/main/profile/README.md#contato).

## Surge uma ideia...

Um problema muito usual no cotidiano das pessoas é que muitos não sabem (ou têm dificuldade) na hora de escolher vegetais e frutas na hora de comprar. Pensando nisso, seria ótimo se existisse uma solução que fornecesse um auxílio para dizer se a fruta/verdura que o cliente selecionou está boa. Assim, propomos a seguinte solução:

Uma implementação em formato de app para o celular, que acessando a câmera auxiliaria muitas pessoas durante este processo, informando se o produto em questão é (ou não) uma boa escolha. 

Ou seja, um aplicativo que te diga se a fruta ou vegetal que você quer comprar está ou não com qualidade para ser consumido! 

## Conseguindo pessoas para a ação

O próximo passo foi criar um grupo disposto a enfrentar esse desafio! A ideia foi proposta no [Programa K](https://www.programak.info), e 8 pesquisadores se identificaram com a solução:

+ Adriano - @ferreira_adriano@discente.ufg.br 
+ Brian - @brian@discente.ufg.br
+ João Vitor - @joaovitor13@discente.ufg.br
+ Juan - @juanqueiroz@discente.ufg.br
+ Larissa - @larissarosa@discente.ufg.br
+ Luan - @luangabriel@discente.ufg.br
+ Lucas - @lucasdejesus@discente.ufg.br
+ Matheus - @carlos_lima@discente.ufg.br 

## Nasce um planejamento

Segundo orientações dos tutores, decidimos tomar por base o seguinte artigo: [Real-Time Quality Assurance of Fruits and Vegetables with
Artificial Intelligence](https://iopscience.iop.org/article/10.1088/1742-6596/2325/1/012055/pdf).
Depois de muita conversa em algumas reuniões, chegamos a conclusão de que esse projeto pode ser repartido em 2 partes principais: o [Mobile](https://github.com/Projeto-Frutas-Vegetais-Programa-K/.github/tree/main/profile#mobile) e a [Inteligência Antificial](https://github.com/Projeto-Frutas-Vegetais-Programa-K/.github/tree/main/profile#inteligência-artificial).

Sabendo disso, nosso grupo decidiu o 1º passo: realizar 2 INSTRUCTIONs (isso é, uma busca por "instrução", uma pesquisa e aprendizado sobre o necessário) em paralelo - um para cada parte do projeto.

### Mobile

Uma questão interessante a se considerar é que o grupo não tinha conhecimento profundo em desenvolvimento mobile, o que foi um grande motivador das nossas escolhas. Os frameworks escolhidos para esse tópico, foram o Kivy e o Flutter, pelos seguintes motivos: O Kivy possibilita desenvolvimento em python (o que facilitaaria a integração com os modelos de Inteligência Artifical posteriormente), e o Flutter já era conhecido de um dos integrantes, além de ser um framework de fácil aprendizado.

### Inteligência Artificial

> A primeira pergunta a se fazer é: Por que usar Inteligência Artificial? (para simplificação, vamos nos referir como IA)

O motivo é simples: ao se determinar a qualidade de frutas e vegetais, muitas pessoas usam técnicas diferentes, algumas vezes baseadas em intuição ou em características que não podem ser abstraídas de uma foto (como o fato de a fruta estar mole por exemplo). Considerando essa "dependência" da situação, seria complexo criar uma solução "universal" que determinasse com acertividade a qualidade desse alimento para o consumo.
Uma das maiores capacidades da IA é a abstração. Sabemos que as Redes Neurais se saem bem em diversos problemas complexos, mas não sabemos exatamente quais características os modelos identificam nos dados. Dessa forma, o grupo acreditou que a capacidade de abstração da IA seria suficiente para uma solução confiável do problema descrito.

> Uma vez decidido isto, devemos seguir para a próxima questão: Por que a ResNet e a Inception? 

Relembrando o tópico anterior, escolhemos um artigo para nos basear. [Neste artigo](https://iopscience.iop.org/article/10.1088/1742-6596/2325/1/012055/pdf), o melhor desempenho foi alcançado por Redes Neurais Convolucionais (do inglês, CNN - Convolutional Neural Networks, é como nos referiremos à elas a partir de agora). Dessa maneira, escolhemos seguir com 2 CNNs. Em seguida, fizemos pesquisas e escolhemos os modelos a serem usados, pois eram CNNs famosas e que dispunham de vasta documentação para consulta.

## Guiando seus passos

Agora, vamos ao mais importante: te ensinar a aprender, como nós fizemos!

Abaixo está uma trilha de consulta dos nossos repositórios para cada parte do projeto, e você poderá seguir o mesmo caminho que nós trilhamos.

### Mobile

Se deseja iniciar no flutter, siga para o repositório: [prototipo-flutter](https://github.com/Projeto-Frutas-Vegetais-Programa-K/prototipo-flutter)

Se deseja iniciar no kivy siga para o repositório: [prototipo-kivy](https://github.com/Projeto-Frutas-Vegetais-Programa-K/prototipo-kivy)

### Inteligência Artificial

Se deseja iniciar na ResNet, siga para o repositório: [Frutas-Vegetais-Resnet](https://github.com/Projeto-Frutas-Vegetais-Programa-K/Frutas-Vegetais-Resnet)

Se deseja iniciar na Inception, siga para o repositório: [Frutas-Vegetais-Inception](https://github.com/Projeto-Frutas-Vegetais-Programa-K/Frutas-Vegetais-Inception)

### Resultados

Um resumo dos principais materiais produzidos nesses passos se encontra no [site do Programa K](https://www.programak.info).

Além disso, o resultado do aplicativo inicial pode ser encontrado neste [repositório](https://github.com/Projeto-Frutas-Vegetais-Programa-K/picky).

### Contato

Se deseja saber mais sobre:

+ o Flutter, fale com @ferreira_adriano@discente.ufg.br ou @brian@discente.ufg.br
+ o Kivy, fale com @carlos_lima@discente.ufg.br ou @juanqueiroz@discente.ufg.br
+ a ResNet, fale com @lucasdejesus@discente.ufg.br ou @joaovitor13@discente.ufg.br
+ a Inception, fale com @larissarosa@discente.ufg.br ou @luangabriel@discente.ufg.br
