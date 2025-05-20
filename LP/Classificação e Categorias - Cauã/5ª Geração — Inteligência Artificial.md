
- Projetadas para expressar **conhecimento** e **inferência**.
    
- Utilizadas em sistemas especialistas, reconhecimento de fala, processamento de linguagem natural, etc.
    
- Menos eficientes em termos de performance.
    

**Exemplo:**

- Prolog

```prolog
pai(joao, maria).
pai(joao, jose).
irmao(X, Y) :- pai(Z, X), pai(Z, Y), X \= Y.
```