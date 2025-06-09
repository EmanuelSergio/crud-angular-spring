# CRUD Angular Spring ⚙️🚀

## Visão Geral 📝
Aplicação full-stack que demonstra operações CRUD (Create, Read, Update, Delete) utilizando Angular no frontend e Spring Boot no backend.

## Tecnologias Utilizadas 💻

### Frontend 🖥️
- Angular 16.2.0 🔷
- Angular Material 16.2.6 🎨
- TypeScript 5.1.3 📜
- RxJS 7.8.0 ⚛️

### Backend (a implementar) 🔧
- Spring Boot 🌱
- Java ☕
- JPA/Hibernate 🗃️

## Estrutura do Projeto 📁

```
crud-angular-spring/
│
├── crud-angular/           # Aplicação frontend Angular
│   ├── src/                # Arquivos fonte
│   ├── angular.json        # Configuração Angular CLI
│   ├── package.json        # Dependências npm
│   └── ...
│
└── ... (backend Spring a ser adicionado)
```

## Instalação e Setup ⚡

### Pré-requisitos ✔️
- Node.js (v14+) 🟢
- npm (v6+) 📦
- Angular CLI (`npm install -g @angular/cli`) 🛠️
- Java JDK 11+ ☕ (para backend)
- Maven (para backend)

### Setup Frontend 🚀
```bash
cd crud-angular
npm install
npm start
```
Abra no navegador: `http://localhost:4200/`

## Desenvolvimento 🛠️

- Use `ng serve` para rodar o servidor de desenvolvimento
- O app recarrega automaticamente ao alterar os arquivos 🔄
- Crie componentes com `ng generate component nome-componente` ➕

## Estilo de Código 🎯

- Segue guidelines oficiais do Angular 📏
- Usa EditorConfig para formatação consistente 🧹
- Modo estrito do TypeScript para segurança de tipos 🔒
- Componentes Angular Material para UI consistente 🎨

## Build para Produção 🏗️

Execute:
```bash
ng build
```
Arquivos compilados ficam no diretório `dist/`.

## Testes 🧪

- Unitários: `ng test` (Karma)
- End-to-end: `ng e2e` (requer configuração adicional)

## Funcionalidades Planejadas 🔮

- Autenticação e autorização de usuários 🔐
- Operações CRUD para recursos ✍️📖✏️❌
- Design responsivo com Material UI 📱💻
- Validação de formulários ✅
- Filtragem, ordenação e paginação de dados 🔍📊