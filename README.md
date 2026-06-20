# Brenda Martins Studio

Site de apresentação de serviços para o **Brenda Martins Studio** —
micropigmentação e estética avançada.

Página única (landing page) construída com HTML, CSS e JavaScript puros,
sem dependências de build. É só abrir o `index.html` no navegador.

## Serviços apresentados
- Design de Sobrancelhas
- Micropigmentação de Sobrancelhas
- Micropigmentação de Lábios
- Remoção de Tatuagem
- Manicure
- Pedicure
- SPA & Relaxamento

## Estrutura
```
index.html      Conteúdo e seções da página
styles.css      Identidade visual (paleta rosé/nude, tipografia)
script.js       Menu mobile e animações de rolagem
images/         Foto da profissional e placeholders (ver images/README.md)
```

## Personalização rápida
- **Foto principal:** adicione `images/brenda.jpg` (ver `images/README.md`).
- **WhatsApp:** troque `5500000000000` pelos números reais em `index.html`.
- **Contatos:** atualize e-mail e Instagram na seção `#contato`.
- **Cores:** ajuste as variáveis `--rose-*` no topo de `styles.css`.

## Como visualizar
Abra o arquivo `index.html` diretamente no navegador, ou rode um servidor local:

```bash
python3 -m http.server 8000
# acesse http://localhost:8000
```
