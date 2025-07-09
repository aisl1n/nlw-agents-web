# NLW Agents

Projeto desenvolvido durante um evento da Rocketseat, focado em demonstrar o uso de agentes inteligentes com React e tecnologias modernas.

## 🚀 Tecnologias Utilizadas

### Frontend

- **React 19.1.0** - Biblioteca principal para construção da interface
- **TypeScript** - Superset do JavaScript com tipagem estática
- **Vite** - Build tool e servidor de desenvolvimento
- **React Router DOM** - Roteamento para aplicações React
- **TanStack React Query** - Gerenciamento de estado e cache para requisições

### Estilização

- **Tailwind CSS 4.1.11** - Framework CSS utilitário
- **Radix UI** - Componentes primitivos acessíveis
- **Lucide React** - Biblioteca de ícones
- **Class Variance Authority** - Utilitário para variações de classes CSS
- **Tailwind Merge** - Merge inteligente de classes do Tailwind

### Qualidade de Código

- **Biome** - Linter e formatador de código
- **Ultracite** - Configuração estendida para Biome

## 🏗️ Padrões de Projeto

- **Component Composition** - Uso de Radix UI para componentes reutilizáveis
- **Custom Hooks** - Gerenciamento de estado com React Query
- **Alias Path** - Importações simplificadas com `@/` para `./src`
- **Atomic Design** - Estrutura de componentes organizados por complexidade

## 📁 Estrutura do Projeto

```
src/
├── components/
│   └── ui/           # Componentes base (shadcn/ui)
├── lib/
│   └── utils.ts      # Utilitários e helpers
├── pages/
│   ├── create-room.tsx
│   └── room.tsx
├── app.tsx           # Componente principal
├── main.tsx          # Ponto de entrada
└── index.css         # Estilos globais
```

## ⚙️ Configuração e Instalação

### Pré-requisitos

- Node.js (versão 16 ou superior)
- npm ou yarn

### Instalação

1. Clone o repositório:

```bash
git clone <repository-url>
cd nlw-agents/web
```

2. Instale as dependências:

```bash
npm install
```

3. Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

4. Abra seu navegador em `http://localhost:5173`

## 🛠️ Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Gera a build de produção
- `npm run preview` - Visualiza a build de produção
- `npm run lint` - Executa o linter (Biome)

## 🎨 Componentes UI

O projeto utiliza componentes baseados no **shadcn/ui** com Tailwind CSS, proporcionando:

- Design system consistente
- Componentes acessíveis por padrão
- Fácil customização e extensibilidade
- Suporte a temas dark/light

## 📱 Funcionalidades

- Criação de salas
- Navegação entre páginas
- Interface responsiva
- Gerenciamento de estado reativo
