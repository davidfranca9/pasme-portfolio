# Portfólio P.A.S.M.E

Site estático e responsivo de portfólio para Social Media.

## Visualizar

Abra `index.html` diretamente no navegador ou inicie um servidor local:

```powershell
python -m http.server 8000
```

Depois acesse `http://localhost:8000`.

## Personalizar

- Textos e projetos: `index.html`
- Cores e layout: `styles.css`
- E-mail do botão de contato: procure por `mailto:` em `index.html`
- Logo: `assets/logo-pasme.jpg`
- Imagens dos projetos: `assets/projetos/`

## Projetos

A seção **Projetos selecionados** exibe trabalhos reais a partir de `assets/projetos/`.
Para adicionar um novo, coloque a imagem nessa pasta e duplique um bloco `.project-card`
em `index.html`, ajustando `src`, `width`, `height`, `alt` e `data-caption`.

Os cards preservam a proporção original da imagem (nada é cortado) e abrem em
visualização ampliada ao clique.
