1. **Análise Léxica**:
    
    - Quebra o código em **tokens**.
        
    - Ex: palavras-chave, identificadores, operadores, etc.
        
2. **Análise Sintática**:
    
    - Usa os tokens para formar a **estrutura gramatical** do programa.
        
    - Resultado: **árvore de análise sintática (parse tree)**.
        
3. **Análise Semântica**:
    
    - Verifica **coerência lógica**.
        
    - Usa uma **Tabela de Símbolos** para rastrear:
        
        - Tipos de dados, variáveis, funções, constantes, etc.
            
4. **Geração de Código Intermediário**:
    
    - Cria uma representação entre o código-fonte e a linguagem de máquina.
        
    - Se assemelha a Assembly.
        
5. **Geração de Código Final**:
    
    - Transforma o código intermediário em código de máquina.