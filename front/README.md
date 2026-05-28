🪚 Gerenciador de Controle de Peças para Marceneiros 

Este projeto é um sistema digital feito sob medida para facilitar a organização, controle de estoque e acompanhamento de cortes na sua marcenaria. O desenvolvimento Fullstack conecta frontend e backend de forma eficiente.

🛠️ Stack Tecnológica 


Frontend: Next.js e React.js para fundamentos e boas práticas em interfaces modernas.


Linguagem: TypeScript para tipagem robusta e um código escalável e sem erros.


Banco de Dados e ORM: PostgreSQL e Prisma ORM para banco de dados relacional e criação de APIs.


Interface: Tailwind CSS e Shadcn UI para estilização rápida e componentes profissionais.


Versionamento: GitHub para colaboração e controle de versão.

🏗️ Arquitetura Principal 


src/actions/: Em vez de concentrar rotas na pasta api, utiliza Server Actions do Next.js para chamar funções diretamente do frontend.


src/components/ui/: Pasta dedicada exclusivamente aos componentes do Shadcn UI.


src/lib/prisma.ts: Evita abrir conexões infinitas com o PostgreSQL no ambiente de desenvolvimento.


Grupos (dashboard): Pastas com parênteses utilizadas para organização lógica e para aplicar layouts específicos sem alterar a URL exibida no navegador.

⚙️ Como Executar o Projeto Localmente 

Clone o repositório.

Instale as dependências.

Crie um arquivo .env na raiz do projeto e configure a URL de conexão com o banco de dados PostgreSQL.

Rode os comandos para sincronizar o banco a partir do arquivo schema.prisma, que contém a modelagem de Projetos, Chapas e Peças.

Inicie o servidor de desenvolvimento.

Abra http://localhost:3000 no navegador para acessar o sistema.