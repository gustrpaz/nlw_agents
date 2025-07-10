# NLW Agents - Frontend

Projeto desenvolvido durante o evento **Next Level Week (NLW)** da **Rocketseat**, focado na criação de uma aplicação com agentes de IA.

## 🚀 Tecnologias Utilizadas

- **React** - Biblioteca para construção da interface
- **TypeScript** - Superset do JavaScript com tipagem estática
- **Vite** - Build tool e dev server
- **Tailwind CSS** - Framework CSS utilitário
- **Lucide React** - Biblioteca de ícones
- **React Hook Form** - Gerenciamento de formulários
- **Zod** - Validação de schemas

## 📁 Estrutura do Projeto

```
src/
├── components/     # Componentes reutilizáveis
├── pages/         # Páginas da aplicação
├── hooks/         # Custom hooks
├── utils/         # Funções utilitárias
├── types/         # Definições de tipos TypeScript
└── styles/        # Arquivos de estilo
```

## 🛠️ Padrões de Projeto

- **Component-Based Architecture** - Componentização da interface
- **Custom Hooks** - Lógica reutilizável encapsulada
- **Type Safety** - Tipagem forte com TypeScript
- **Form Validation** - Validação de dados com Zod
- **Responsive Design** - Interface adaptável com Tailwind CSS

## ⚙️ Setup e Configuração

### Pré-requisitos

- Node.js (versão 18 ou superior)
- npm ou yarn

### Instalação

1. Clone o repositório:

```bash
git clone <url-do-repositorio>
cd nlw-agents
```

2. Instale as dependências:

```bash
npm install
```

3. Configure as variáveis de ambiente:

```bash
cp .env.example .env.local
```

4. Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

5. Acesse a aplicação em `http://localhost:5173`

## 📝 Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Gera build de produção
- `npm run preview` - Visualiza o build de produção
- `npm run lint` - Executa o linter

## 🎨 Estilização

O projeto utiliza **Tailwind CSS** para estilização, proporcionando:

- Design system consistente
- Classes utilitárias
- Responsividade nativa
- Customização através do `tailwind.config.js`

---

Desenvolvido com ❤️ durante o **NLW** da **Rocketseat**
