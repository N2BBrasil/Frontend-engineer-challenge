# Show me the code - N2B

## Desafio Frontend Engineer

A empresa de telefonia X, especializada em chamadas de longa distância nacional, vai
colocar um novo produto no mercado chamado FaleMais.
Normalmente um cliente X pode fazer uma chamada de uma cidade para outra pagando
uma tarifa fixa por minuto, com os preço sendo pré-definido em uma lista com os códigos DDDs
de origem e destino

| Origem        | Destino       | $/min |
| ------------- |:-------------:| -----:|
| 011           | 016           |  1.90 |
| 016           | 011           |  2.90 |
| 011           | 017           |  1.70 |
| 017           | 011           |  2.70 |
| 011           | 018           |  0.90 |
| 018           | 011           |  1.90 |

Com o produto FaleMais, o cliente adquire um plano e pode falar de graça até um 
determinado tempo (em minutos) e só paga os minutos excedentes. Os minutos excedentes 
tem um acrescimo de 10% sobre a tarifa normal do minuto. Os planos são FaleMais 30 (30 
minutos), FaleMais 60 (60 minutos) e FaleMais 120 (120 minutos).

A empresa X, preocupada com a transparência junto aos seus clientes, quer disponibilizar 
uma página na web onde o cliente pode calcular o valor da ligação. Ali, o cliente pode 
escolher os códigos das cidades de origem e destino, o tempo da ligação em minutos e 
escolher qual o plano FaleMais. O sistema deve mostrar dois valores: 

(1) o valor da ligação com o plano e (2) sem o plano.

![Valores dos Planos](https://i.imgur.com/1j8LkJ2.png)

*Obs: O Backend está exposto em 2 rotas:*

- Referente aos DDDs, incluindo seus possíveis destinos e tarifas:

`GET` -> `https://mysterious-reaches-49012.herokuapp.com/ddd`

- Referente aos Planos, contendo o nome do plano e os minutos correspondentes para cada: 

`GET` -> `https://mysterious-reaches-49012.herokuapp.com/planos`


## Avaliação

- Para o desenvolvimento utilize Angular5 

## Importante
- Clareza e organização do código
- Organização dos branches e commits
   *não é preciso usar um processo de versionamento como git-flow, olharemos mais para os commits em si*
- `README.md` explicativo e conciso
- Uso de linter e boas práticas

*Referencias:*

https://chris.beams.io/posts/git-commit/
http://nvie.com/posts/a-successful-git-branching-model/
https://angular.io/guide/styleguide

## Extras

- Interface gráfica bem acabada
- Uso avançado de TypeScript e/ou Angular
- Boas práticas e patterns de `RxJS` 
- Testes e2e e unitários
- Tente usar as boas práticas de codificação e se sinta a vontade caso queira extender um
    pouco os requisitos para mostrar seus conhecimentos.

Sinta-se livre para utilizar qualquer biblioteca externa, principalmente para os testes.

## Como começar

Faça um `fork` desse projeto e ao terminar, envie um email para `contato@n2bbrasil.com`

Fique a vontade para compartilhar dúvidas nas issues ou mandar para o email acima.
