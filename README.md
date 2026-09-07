# Soul Design — Landing Page de Alta Conversão

Landing page institucional e de conversão desenvolvida em **React 19**, **Vite** e **Tailwind CSS v4**, com animações fluidas via **GSAP** e arquitetura modular de injeção dinâmica de SEO por nicho de atuação.

---

## Destaques de Engenharia

- **Injeção Dinâmica de SEO:** Utiliza um plugin customizado no pipeline do Vite (`transformIndexHtml`) que altera dinamicamente meta tags (`title`, `description`) de acordo com o nicho de mercado selecionado via variáveis de ambiente (`VITE_NICHE`).
- **Animações Fluidas:** Efeitos visuais e microinterações de alto impacto construídos com GSAP para engajamento e retenção de usuários.
- **Integração de Contato:** Formulário com envio assíncrono conectado ao EmailJS.
- **Design Moderno:** Construído com a nova engine do Tailwind CSS v4 para build ultra-rápido e zero runtime overhead.

---

## Tecnologias Utilizadas

- **Core:** React 19, Vite
- **Estilização:** Tailwind CSS v4, Autoprefixer
- **Animações:** GSAP (GreenSock Animation Platform)
- **Ícones:** Lucide React
- **Serviços:** EmailJS Browser SDK

---

## Estrutura de Pastas

```
Soul-Design/
├── src/
│   ├── assets/        # Recursos estáticos da aplicação
│   ├── components/    # Componentes reutilizáveis de interface
│   ├── config/        # Configuração de nichos e dados dinâmicos de SEO
│   ├── data/          # Mock data e textos estruturados
│   └── utils/         # Funções utilitárias e helpers
├── public/            # Favicon e ativos públicos estáticos
├── docs/assets/       # Imagens de preview e documentação
└── vite.config.js     # Configuração do Vite com transformador de SEO
```

---

## Como Executar Localmente

### Pré-requisitos
- Node.js (v18+)
- npm ou yarn

### Instalação e Execução
```bash
# Instalar dependências
npm install

# Iniciar servidor de desenvolvimento
npm run dev

# Gerar build de produção
npm run build
```

---

## Configuração de Nichos (Variáveis de Ambiente)

Para alternar o nicho de renderização de SEO, crie um arquivo `.env` baseado nas opções disponíveis em `src/config/niches.js`:

```env
# Exemplo: corretores | distribuidoras | default
VITE_NICHE=corretores
```
