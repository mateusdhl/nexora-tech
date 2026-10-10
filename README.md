# Nexora Tech — Site corporativo conceitual

Projeto 03 da coleção de demonstrações para o portfólio da **HoraCode**.

## Tecnologias
React 19, TypeScript, Vite, Tailwind CSS v3 e lucide-react.

## Como executar

```bash
npm install
npm run dev
```

Abra o endereço informado pelo Vite (geralmente http://localhost:5173).

Para gerar a versão de produção:

```bash
npm run build
npm run preview
```

## O que o projeto inclui

- Landing page responsiva com hero e painel gráfico criado em CSS.
- Quatro serviços e apresentação de processo em quatro etapas.
- Três cases conceituais com filtros por categoria.
- Seção sobre a empresa, FAQ expansível e formulário validado.
- Navegação móvel e estilos acessíveis para foco e movimento reduzido.

## Formulário

O formulário **não envia dados a um servidor**. Ele utiliza `mailto:` para preparar um e-mail no aplicativo de e-mail do visitante. Troque `CONTACT_EMAIL` em `src/App.tsx` por um endereço real para testar o fluxo. Para receber leads profissionalmente, implemente um backend ou serviço de formulário com validação, proteção antispam e política de privacidade.

## Aviso de uso

Nexora Tech e todos os projetos são **fictícios/conceituais**. Nenhum dado, case, cliente ou resultado apresentado deve ser interpretado como resultado real. Substitua o conteúdo antes de vender ou publicar como projeto de cliente. O website carrega fontes do Google Fonts, que requerem conexão à internet.

## Arquivos principais

- `src/App.tsx` — componentes e comportamento da interface.
- `src/data/content.ts` — serviços, cases e FAQ.
- `src/styles.css` — estilos visuais e Tailwind.
- `tailwind.config.js` — configuração do tema.

## Deploy na Vercel

Suba o repositório ao GitHub, importe-o na Vercel e use o preset Vite, com `npm run build` e pasta de saída `dist`.
