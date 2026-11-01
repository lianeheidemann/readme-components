# Links de imagens SVG para o GitHub

Guia rápido para usar imagens SVG no README do GitHub. Troque `SEU_USUARIO`, `REPO` e os nomes de tecnologias pelos seus.

---

## 1. Como inserir um SVG

### Markdown
```md
![Logo](imagens/logo.svg)
```

### HTML (permite definir tamanho)
```html
<img src="imagens/logo.svg" width="40" height="40" alt="Logo">
```

### Arquivo do próprio repositório (link absoluto)
```
https://raw.githubusercontent.com/SEU_USUARIO/REPO/main/imagens/logo.svg
```

### Centralizado
```html
<p align="center">
  <img src="imagens/logo.svg" width="120" alt="Logo">
</p>
```

---

## 2. Shields.io — badges

Formato: `https://img.shields.io/badge/TEXTO-COR?style=ESTILO&logo=LOGO&logoColor=white`

Estilos: `flat`, `flat-square`, `plastic`, `for-the-badge`, `social`

```md
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)
```

### Badges dinâmicos do repositório
```md
![Stars](https://img.shields.io/github/stars/SEU_USUARIO/REPO?style=flat-square)
![Forks](https://img.shields.io/github/forks/SEU_USUARIO/REPO?style=flat-square)
![Licença](https://img.shields.io/github/license/SEU_USUARIO/REPO?style=flat-square)
![Último commit](https://img.shields.io/github/last-commit/SEU_USUARIO/REPO?style=flat-square)
![Seguidores](https://img.shields.io/github/followers/SEU_USUARIO?style=social)
```

---

## 3. Skill Icons — vários ícones em uma linha

Formato: `https://skillicons.dev/icons?i=ICONE1,ICONE2,...`

```md
![Skills](https://skillicons.dev/icons?i=js,ts,html,css,react,nodejs,python,git,docker,vscode)
```

Opções extras:
- Tema: `&theme=light` ou `&theme=dark`
- Ícones por linha: `&perline=5`

```md
![Skills](https://skillicons.dev/icons?i=js,ts,react,python,git&theme=light&perline=5)
```

---

## 4. Devicon — ícones individuais

Formato: `https://cdn.jsdelivr.net/gh/devicons/devicon/icons/NOME/NOME-original.svg`

```html
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" alt="Python">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" alt="JavaScript">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="40" alt="React">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="40" alt="Node.js">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="40" alt="Git">
```

Variações comuns: `-original`, `-plain`, `-line`, `-original-wordmark`, `-plain-wordmark`

---

## 5. Simple Icons — logos de marcas

Formato: `https://cdn.simpleicons.org/NOME` ou `https://cdn.simpleicons.org/NOME/COR`

```html
<img src="https://cdn.simpleicons.org/github" width="32" alt="GitHub">
<img src="https://cdn.simpleicons.org/python/3776AB" width="32" alt="Python">
<img src="https://cdn.simpleicons.org/linkedin/0A66C2" width="32" alt="LinkedIn">
```

---

## 6. GitHub Readme Stats — estatísticas do perfil

```md
![Stats](https://github-readme-stats.vercel.app/api?username=SEU_USUARIO&show_icons=true&theme=tokyonight)
![Linguagens](https://github-readme-stats.vercel.app/api/top-langs/?username=SEU_USUARIO&layout=compact&theme=tokyonight)
![Repo](https://github-readme-stats.vercel.app/api/pin/?username=SEU_USUARIO&repo=REPO&theme=tokyonight)
```

Temas: `default`, `dark`, `radical`, `merko`, `gruvbox`, `tokyonight`, `onedark`, `dracula`

### Streak (sequência de contribuições)
```md
![Streak](https://streak-stats.demolab.com?user=SEU_USUARIO&theme=tokyonight)
```

---

## 7. Typing SVG — texto animado

```md
![Typing](https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&center=true&vCenter=true&width=500&lines=Olá,+eu+sou+Fulano!;Desenvolvedor+Full+Stack)
```

Parâmetros úteis: `font`, `size`, `color`, `center`, `width`, `lines` (separadas por `;`, espaços como `+`)

---

## 8. Contador de visitas

```md
![Visitas](https://komarev.com/ghpvc/?username=SEU_USUARIO&color=blue&style=flat-square)
```

---

## 9. Imagem diferente para tema claro e escuro

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="imagens/logo-escuro.svg">
  <source media="(prefers-color-scheme: light)" srcset="imagens/logo-claro.svg">
  <img src="imagens/logo-claro.svg" width="200" alt="Logo">
</picture>
```

---

## 10. Dicas

- O GitHub remove JavaScript de SVGs; animações em CSS ou SMIL funcionam.
- Prefira HTML `<img>` quando precisar controlar largura e altura.
- Sempre preencha o `alt` para acessibilidade.
- Serviços externos (stats, streak) podem ficar fora do ar às vezes; para algo crítico, salve o SVG no próprio repositório.
- Para ver todos os nomes de ícones: skillicons.dev, devicon.dev e simpleicons.org.
