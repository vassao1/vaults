
- Desenvolvida com base em **lógica formal**.
    
- Muito usada em IA.
    
- Define fatos e regras; usa inferência lógica.

```prolog
pai(joao, maria).
avo(X,Y) :- pai(X,Z), pai(Z,Y).
```