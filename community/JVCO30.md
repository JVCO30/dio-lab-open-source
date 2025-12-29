UTILIZE BOAS PRATICAS NO SEU COMMIT:


Diretrizes Essenciais
Separe o assunto do corpo com uma linha em branco: Isso permite que ferramentas como git log exibam o assunto de forma concisa.
Limite o assunto a 50 caracteres: Um limite rigoroso ajuda a manter as mensagens legíveis em várias interfaces [1].
Inicie o assunto com letra maiúscula: Padrão de capitalização para maior clareza.
Não termine o assunto com ponto final: Mantenha a concisão e a estética.
Use o modo imperativo no assunto: Escreva como um comando, como "Adicionar", "Corrigir" ou "Mudar", em vez de "Adicionando", "Corrigido" ou "Mudanças" [1].
Use o corpo para explicar o quê e o porquê: Descreva o contexto e a justificativa para a mudança, não apenas como ela foi feita [1]. 
Exemplo de um Bom Commit
Corrigir erro de autenticação do usuário

A autenticação falhava quando o campo de email continha espaços
em branco no início ou no fim. O problema foi resolvido com a
adição de uma função de trim() no valor do email antes da validação.
Formato Recomendado com Tipo (Convenção Angular/Conventional Commits)
Muitas equipes utilizam um prefixo para categorizar o tipo de mudança, o que facilita a automação e a leitura [1]: 
tipo: Assunto do commit
Tipos comuns incluem:
feat (feature): Uma nova funcionalidade [1].
fix (correção): Uma correção de bug [1].
docs (documentação): Alterações na documentação [1].
style (estilo): Formatação, ponto e vírgula ausentes (sem mudanças lógicas) [1].
refactor (refatoração): Uma mudança de código que não corrige um bug nem adiciona um recurso [1].
test (teste): Adição ou refatoração de testes [1].
chore (tarefa/geral): Outras alterações que não modificam o código fonte ou de teste (ex: atualização de dependências) [1]. 
Exemplo:
feat: Adicionar funcionalidade de login social via Google
Seguir essas normas melhora significativamente a organização e a manutenção do histórico do seu projeto.
