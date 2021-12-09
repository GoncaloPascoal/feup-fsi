## Grupo 1 - Conceitos e Terminologia de Segurança Informática

**1.1.**
* Roubar credenciais (passwords, dados bancários)
* Usar os recursos de hardware (processador, GPU) para minar criptomoedas

**1.2.**
* Trusted Third Party (TTP) - ator em que depositamos confiança
* Utilizador normal do serviço
* Atacante (utilizador malicioso)

**1.3.**
Tipo|Exemplo
----|-------
2   |update de segurança feito anualmente
1   |terramoto
3   |string de formatação que causa *crash*
1   |antigo colaborador em conflito
2   |utilização de `strcpy` sem teste de tamanho
2   |duplo `free`
3   |ficheiro `bitmap` que causa reescrita de endereço na *heap*
1   |*data breach*

**1.4.** 

Um ator é qualquer entidade que interage com um sistema, e um ativo algo
com valor para um ator (informação, recursos monetários, infra-estrutura). A segurança
tem como objetivo prevenir a perda de valor dos ativos através do abuso do sistema
por atores maliciosos (quebra de confidencialidade, integridade e/ou disponibilidade).

Para que um sistema seja confiável, a segurança deste deve ser concebida e implementada
de forma sistemática, o que começa pela definição do modelo de ameaças do sistema
(ativos a proteger, atacantes a enfrentar, tipos de ataques a considerar, perímetro
de segurança, pontos de ataque), o seu modelo de confiança (em que atores e componentes do sistema depositamos a nossa confiança) e a sua política de segurança
(o conjunto de mecanismos que garantem a segurança do sistema contra as ameaças
definidas anteriormente, assumindo também que o modelo de confiança não é violado).

## Grupo 2 - Controlo

**2.1.**
Endereço|Conteúdo
-|-
Endereço mais elevado|3
.|4
.|2
.|1
Endereço mais baixo|

**2.2.** A afirmação é falsa. Um overflow de apenas um byte permite modificar o byte
menos significativo do frame pointer da função anterior na *call stack*. Em certas
circunstâncias especiais, como por exemplo numa vulnerabilidade off-by-1 da função
`realpath` pode até permitir ao atacante a obtenção de privilégios root.