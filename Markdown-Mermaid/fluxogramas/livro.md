``` mermaid
flowchart TD
A{Você quer começar a ler um livro?} 
A --> |Sim| B{Qual gênero você gosta?}
A --> |Não| C[Dê uma chance, livros são legais!]
B --> |Romance policial| D[Então leia Morte no Nilo da Agatha Christie]
B --> |Romance| E[Então leia Melhor do que Nos Filmes da Lynn Painter]
B --> |Clássico| F[então leia Dom Casmurro do Machado de Assis]
D --> G[Ao terminar me conte o que achou!]
E --> G[Ao terminar me conte o que achou!]
F --> G[Ao terminar me conte o que achou!]

```