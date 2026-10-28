# Córtex Fisio - Landing Page

Site estático de vendas para Córtex Fisio - plataforma de pesquisa científica para fisioterapeutas.

## Estrutura

```
cortex-fisio/
├── index.html          # Página principal
├── support.js          # JavaScript de suporte
├── assets/             # Imagens, vídeos e recursos
├── _ds/                # Design system (estilos e componentes)
├── package.json        # Configuração do projeto
├── .gitignore          # Arquivos a ignorar no Git
└── README.md           # Este arquivo
```

## Como rodar localmente

```bash
# Opção 1: Python (mais simples)
python -m http.server 3000

# Opção 2: Node.js (se tiver instalado)
npm start
```

Depois, abra `http://localhost:3000` no navegador.

## Deploy no Vercel

1. Crie uma conta em [vercel.com](https://vercel.com)
2. Conecte este repositório GitHub
3. Clique em "Deploy"
4. Pronto! Seu site estará online

## Arquivo principal

- **index.html** - Contém toda a página em um arquivo único com CSS e JS integrado
- Responsivo e otimizado para mobile
- Tema com variáveis CSS customizáveis

## Recursos

- Logo e assets em `assets/`
- Video demo em `assets/demo.mp4`
- Design system modernista em `_ds/`
- Suporte a animações e efeitos visuais

---

Criado com Claude Design
