```mermaid
sequenceDiagram 
participant Leitor
participant Sistema

    Leitor->>Sistema: Quero uma sugestão de livro
    Sistema-->>Leitor: Você quer começar a ler um livro?
    Leitor-->>Sistema: Sim
    Sistema-->>Leitor: Qual gênero você gosta?
    Leitor-->>Sistema: Romance
    Sistema-->>Leitor: Sugestão: "Melhor do que Nos Filmes" de Lynn Painter
    Leitor-->>Sistema: Obrigado!
    Sistema-->>Leitor: Ao terminar, me conte o que achou!
```