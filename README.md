# commit-conventions
Padrões de Commit


<b><mark>feat</mark></b>
<p>Indicao o desenvolvimento de uma nova feature ao projeto</p>
Exemplo: Acréscimo de um serviço, funcionalidade, endpoint, etc

<b>refactor</b>
<p>Usado quando houver uma refatoração de código que não tenha qualquer tipo de impacto na lógica/regras de negócio do sistema.</p>
Exemplo: Mudanças de código após um code review

<b>perf</b>
<p>Indica uma alteração que melhorou a performance do sistema.</p>
Exemplo: Alterar ForEach por while, melhorar a query ao banco, etc.

<b>fix</b>
<p>Utilizado quando há correção de erros que estão gerando bugs no sistema.</p>
Exemplo: Aplicar tratativa para uma função que não está tendo o comportamento esperado e retornando erro.

<b>test</b>
<p>Indica qualquer tipo de criação ou alteração de códigos de teste</p>
Exemplo: Criação de Testes Unitários

<b>docs</b>
<p>Usado quando há mudanças na documentação do projeto.</p>
Exemplo: Adicionar informações na documentação da API, mudar o README, etc.

<b>style</b>
<p>Empregado quando há mudanças de formatação e estilo do código que não alteram o sistema de nenhuma forma.</p>
Exemplo: Mudar o style-guide, mudar de convenção lint, arrumar indentações, remover espaços em brancos, remover comentários, etc.

<b>chore</b>
<p>Indica mudanças no projeto que não afetem o sistema ou arquivos de testes. São mudanças de desenvolvimento.</p>
Exemplo: Mudar regras do eslint, adicionar prettier, adicionar mais extensões de arquivos ao .gitignore.

<b>build</b>
<p>Utilizada para indicar mudanças que afetam o processo de build do projeto ou dependências externas.</p>
Exemplo: Gulp, adicionar/remover dependências do npm, etc.

<b>ci</b>
<p>Utilizada para mudanças nos arquivos de configuração de CI.</p>
Exemplo: Circle, Travis, BrowserStack, etc.

<b>revert</b>
<p>Indica a reversão de um commit anterior.</p>
Exemplo: revert: back to a215868 commit




