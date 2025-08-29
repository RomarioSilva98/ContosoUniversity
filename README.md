<h1>🎓 Razor Pages com Entity Framework Core - Tutorial Microsoft</h1>

<h2>📋 Descrição do Projeto</h2>
<p>Este projeto foi desenvolvido seguindo o tutorial oficial da Microsoft sobre Razor Pages com Entity Framework Core em ASP.NET Core. A aplicação demonstra as funcionalidades essenciais de um CRUD completo com operações de criação, leitura, atualização e exclusão de dados.</p>

<h2>🎯 Objetivo</h2>
<p>Implementar uma aplicação web completa utilizando as melhores práticas do ASP.NET Core com Razor Pages e Entity Framework Core, seguindo o tutorial em 8 partes da documentação oficial da Microsoft.</p>

<h2>🛠️ Tecnologias Utilizadas</h2>

<h3>Backend</h3>
<ul>
  <li><b>ASP.NET Core 6.0</b> - Framework web</li>
  <li><b>Razor Pages</b> - Modelo de aplicação web</li>
  <li><b>Entity Framework Core</b> - ORM para acesso a dados</li>
  <li><b>SQL Server</b> - Banco de dados relacional</li>
  <li><b>LINQ</b> - Consultas integradas à linguagem</li>
</ul>

<h3>Frontend</h3>
<ul>
  <li><b>HTML5</b> - Estrutura das páginas</li>
  <li><b>CSS3</b> - Estilização básica</li>
  <li><b>Razor Syntax</b> - Integração backend-frontend</li>
  <li><b>Bootstrap</b> - Framework CSS opcional</li>
</ul>

<h2>📚 Partes do Tutorial Implementadas</h2>

<h3>1️⃣ Get Started - Introdução</h3>
<ul>
  <li>Configuração do ambiente de desenvolvimento</li>
  <li>Criação do projeto Razor Pages</li>
  <li>Configuração básica do Entity Framework Core</li>
  <li>Modelo de dados inicial</li>
</ul>

<h3>2️⃣ Create, Read, Update, and Delete - CRUD</h3>
<ul>
  <li>Implementação das operações básicas de CRUD</li>
  <li>Páginas para criação de registros</li>
  <li>Visualização de detalhes</li>
  <li>Edição e exclusão de dados</li>
</ul>

<h3>3️⃣ Sort, filter, page, and group - Ordenação e Filtros</h3>
<ul>
  <li>Implementação de ordenação de dados</li>
  <li>Sistema de filtragem por diferentes critérios</li>
  <li>Paginação de resultados</li>
  <li>Agrupamento de dados</li>
</ul>

<h3>4️⃣ Migrations - Migrações de Banco</h3>
<ul>
  <li>Gerenciamento de migrações do Entity Framework</li>
  <li>Atualização do esquema de banco de dados</li>
  <li>Controle de versão do modelo de dados</li>
</ul>

<h3>5️⃣ Create a complex data model - Modelo Complexo</h3>
<ul>
  <li>Desenvolvimento de modelo de dados complexo</li>
  <li>Relações entre entidades (1-1, 1-N, N-N)</li>
  <li>Validações de dados avançadas</li>
  <li>Configuração do contexto de dados</li>
</ul>

<h3>6️⃣ Read related data - Leitura de Dados Relacionados</h3>
<ul>
  <li>Consulta de dados com relacionamentos</li>
  <li>Carregamento eager vs lazy loading</li>
  <li>Exibição de dados relacionados nas views</li>
  <li>Otimização de consultas com joins</li>
</ul>

<h3>7️⃣ Update related data - Atualização de Dados Relacionados</h3>
<ul>
  <li>Operações de atualização em dados relacionados</li>
  <li>Manipulação de coleções e relacionamentos</li>
  <li>Validação de integridade referencial</li>
  <li>Transações e consistência de dados</li>
</ul>

<h3>8️⃣ Handle concurrency conflicts - Concorrência</h3>
<ul>
  <li>Detecção e tratamento de conflitos de concorrência</li>
  <li>Padrões de resolução de conflitos</li>
  <li>Controle de concorrência otimista</li>
  <li>Tratamento de exceções de simultaneidade</li>
</ul>

<h2>🚀 Como Executar</h2>

<p><b>Pré-requisitos</b></p>
<ul>
  <li>.NET 6.0 SDK ou superior</li>
  <li>SQL Server (local ou Express)</li>
  <li>Visual Studio 2022 ou VS Code</li>
</ul>

<p><b>Comandos de Configuração</b></p>
<pre>
dotnet tool install --global dotnet-ef
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
</pre>

<p><b>Execução do Projeto</b></p>
<pre>
dotnet restore
dotnet ef database update
dotnet run
</pre>

<h2>🏗️ Estrutura do Projeto</h2>

<h3>📁 Organização de Arquivos</h3>
<ul>
  <li><b>Pages/</b> - Páginas Razor com code-behind</li>
  <li><b>Models/</b> - Entidades e modelos de dados</li>
  <li><b>Data/</b> - Contexto do banco e configurações do EF</li>
  <li><b>Migrations/</b> - Arquivos de migração do banco</li>
  <li><b>wwwroot/</b> - Arquivos estáticos (CSS, JS, imagens)</li>
</ul>

<h2>🎯 Conceitos Aprendidos</h2>

<h3>✅ Padrão MVC com Razor Pages</h3>
<ul>
  <li>Separação de concerns (preocupações)</li>
  <li>PageModel e binding de dados</li>
  <li>Handler methods para ações</li>
</ul>

<h3>✅ Entity Framework Core</h3>
<ul>
  <li>Code-first approach</li>
  <li>Configuração de DbContext</li>
  <li>Fluent API para mapeamento</li>
  <li>LINQ queries</li>
</ul>

<h3>✅ Boas Práticas de Desenvolvimento</h3>
<ul>
  <li>Validação de dados</li>
  <li>Tratamento de erros</li>
  <li>Segurança básica (XSS, CSRF)</li>
  <li>Performance e otimização</li>
</ul>

<h2>📖 Recursos Adicionais</h2>

<h3>🔗 Documentação Oficial</h3>
<ul>
  <li>ASP.NET Core Razor Pages: https://docs.microsoft.com/aspnet/core/razor-pages</li>
  <li>Entity Framework Core: https://docs.microsoft.com/ef/core</li>
  <li>Tutorial Completo: https://docs.microsoft.com/aspnet/core/data/ef-rp/intro</li>
</ul>

<h3>🎓 Próximos Passos</h3>
<ul>
  <li>Implementar autenticação e autorização</li>
  <li>Adicionar API RESTful</li>
  <li>Implementar testes unitários e de integração</li>
  <li>Configurar deployment em nuvem</li>
</ul>

<h2>👥 Desenvolvido por</h2>
<p>Romário Silva</p>

<h2>📄 Licença</h2>
<p>Este projeto foi desenvolvido para fins educacionais seguindo o tutorial oficial da Microsoft.</p>
