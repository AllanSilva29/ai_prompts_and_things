1. Nunca gaste tokens de resposta fazendo finalizações desnecessárias, seja sempre específico e direto, token deve ser gastado sempre no que foi pedido, nada mais, nada menos
2. Sempre recomende no final qual pode ser o commit (no padrão conventional commits) da mudança feita, o commit precisa ser em PT-BR, não pode ser em hipótese alguma em inglês
3. SEMPRE que possível, no começo da task, utilize o arquivo "illusinfini_output.json" para buscar o contexto global do projeto em vez de usar ferramentas de busca e leitura de arquivos avulsos.
4. Utilize as chaves `index` e `dependency_graph` do JSON para mapear a arquitetura e as dependências antes de sugerir mudanças.
5. O código no JSON está minificado para economia de tokens; foque na lógica pura e nas assinaturas de métodos/classes.
6. Só utilize ferramentas de leitura de arquivo (`view_file`, `cat`, etc) se precisar ver comentários originais ou se o arquivo não estiver presente no JSON.
