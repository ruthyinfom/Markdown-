``` mermaid
flowchart TD 
A[Escolha um número que seja par] --> B[Verificar se o número é par ]  
B --> C{Quando dividido por 2 tem resto 0?}
C --> |Sim| D[Então ele é par! Parabéns!]
C --> |Não| E[Então ele é ímpar! Tente de novo.]
E --> A

``` 