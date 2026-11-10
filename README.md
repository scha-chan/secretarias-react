# Secretarias React

Aplicação web desenvolvida com **React 17** e **TypeScript**, utilizando Create React App como base.

## Tecnologias Principais

| Tecnologia | Versão |
|---|---|
| React | 17.0.2 |
| TypeScript | 4.1.5 |
| React Router DOM | 6.3.0 |
| React Redux | 7.2.0 |

## Bibliotecas Utilizadas

### UI & Estilização
- **MUI (Material UI)** `^5.8.5` — Componentes de interface
- **MUI Icons Material** `^5.8.4` — Ícones do Material Design
- **MUI Lab** `^5.0.0-alpha.84` — Componentes experimentais do MUI
- **MUI X Data Grid** `^5.12.2` — Tabela de dados avançada
- **@emotion/react** `^11.9.3` — CSS-in-JS (dependência do MUI)
- **@emotion/styled** `^11.9.3` — Styled components (dependência do MUI)
- **@fontsource/roboto** `^4.5.3` — Fonte Roboto
- **@headlessui/react** `^1.6.5` — Componentes acessíveis sem estilo
- **react-icons** `^4.3.1` — Biblioteca de ícones

### Formulários & Validação
- **React Hook Form** `^7.17.1` — Gerenciamento de formulários
- **@hookform/resolvers** `^2.8.1` — Resolvers para validação
- **Yup** `^0.32.9` — Validação de esquemas
- **class-validator** `^0.13.1` — Validação por decorators

### Gerenciamento de Estado
- **Redux Toolkit** `^1.5.1` — Gerenciamento de estado simplificado
- **react-redux** `^7.2.0` — Bindings React para Redux

### Gráficos
- **@devexpress/dx-react-chart** `^3.0.3` — Componentes de gráficos
- **@devexpress/dx-react-chart-material-ui** `^3.0.3` — Gráficos com tema Material UI
- **@devexpress/dx-react-core** `^3.0.3` — Core do DevExtreme React

### Utilitários
- **moment** `^2.29.3` — Manipulação de datas
- **uuid** `^8.3.2` — Geração de IDs únicos

## Como executar

Instale as dependências:

```bash
npm install
```

Inicie o servidor de desenvolvimento:

```bash
npm start
```

A aplicação estará disponível em [http://localhost:3000](http://localhost:3000).

A página recarrega automaticamente ao salvar alterações. Erros de lint são exibidos no console.

## Scripts disponíveis

| Script | Descrição |
|---|---|
| `npm start` | Inicia o servidor de desenvolvimento |
| `npm run build` | Gera o build de produção na pasta `build/` |
| `npm test` | Executa os testes |
| `npm run eject` | Ejeta as configurações do Create React App |
