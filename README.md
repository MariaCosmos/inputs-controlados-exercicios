
# Inputs Controlados

Caso não lembre como funciona o processo de entrega, clique [**aqui**](https://github.com/labenuexercicios/instrucoes-entrega)


## Como eu vou executar os exercícios?
Para o exercício de hoje, vamos utilizar um template! Dentro desse template vocês vão encontrar uma estrutura para trabalharmos com diferentes tipos de input! :) 


Para executar este exercício, você pode criar uma nova aplicação React, utilizar o **CodeSandbox** ou usar este template do repositório.
- Caso use este template, lembre-se de dar um `npm install` assim que baixar! 
- Caso estiver usando o codeSandBox, pode usar esse template aqui: 

Caso queira criar uma nova aplicação React, basta copiar os conteúdos deste repositório e colar dentro da pasta do seu projeto criado.

# **Observação: A aplicação não vai funcionar até você finalizar o exercício 2!**

# Exercício 1

Primeiro, vamos analisar todo o código que vocês estão recebendo. 

- Observe o `App.js`, o que você consegue visualizar que já conhece? 
- Entende o `<GlobalStyles/>`?
- Analize os componentes dentro do App.js, quantos e quais componentes estão sendo chamados aqui?

- Agora analize o `JSX` de cada um desses componentes.
- Você vai perceber que o componente `MainPage` é o componente principal do projeto. É lá onde está armazenado os componentes `NameForm` e `ConfirmationForm`. 
- Foi criada uma lógica de renderização na linha 39 que vai ser usada por você nos próximos exercícios. Você não precisa entender 100% como ela funciona por enquanto.
- Agora analize o componente `NameForm`. Ele é uma versão componentizada do exercício de hoje de manhã durante a aula. Perceba que, agora, ele precisa receber `props` para funcionar corretamente.
- O componente `ConfirmationForm` está incompleto. Seu trabalho será criar esse componente e administrar o controle dos inputs que serão pedidos a seguir.


# Exercício 2

Agora vamos incrementar o formulário que trabalhamos hoje de manhã



# Exercício 3
 Implemente a função de evoluir o Pokemon. Nessa função de onClick, você precisa modificar o estado criado no App.js para que, ao clicar, o Pokemon evolua pra sua próxima forma, se isso for possível.
Perceba que alguns pokemons evoluem e outros não.
Para isso, você precisa modificar os dados de dentro do objeto salvo no useState. Através de um spread operator, modifique apenas os dados necessários para que o pokemon evolua: 

- Cor
- Imagem
- Nome
- Tipo
- Evoluido (perceba que isso é um boolean, se ele já estiver evoluído, deve ser true; caso contrário, false.)
- Peso

Depois disso, crie novos cards com pokemons diferentes para praticar :) 
