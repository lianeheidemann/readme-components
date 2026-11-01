# Links de imagens SVG para o GitHub

Guia visual: cada seção mostra a imagem renderizada e, logo abaixo, o código para copiar.

---

## 1. Como inserir um SVG

### Markdown

<img src="https://cdn.simpleicons.org/github/white" width="30%" align="left" alt="GitHub">
<br clear="left">

```md
![GitHub](https://cdn.simpleicons.org/github/white)
```

### HTML (permite definir tamanho)

<img src="https://cdn.simpleicons.org/github/white" width="40" height="40" alt="GitHub">

```html
<img src="https://cdn.simpleicons.org/github/white" width="40" height="40" alt="GitHub">
```

### Arquivo do próprio repositório

Coloque o SVG numa pasta do repositório e aponte para ele:

```md
![Logo](imagens/logo.svg)
```

Ou com link absoluto:

```
https://raw.githubusercontent.com/lianeheidemann/readme-components/develop/imagens/logo.svg
```

### Centralizado

<p align="center">
  <img src="https://cdn.simpleicons.org/github/white" width="80" alt="GitHub">
</p>

```html
<p align="center">
  <img src="https://cdn.simpleicons.org/github/white" width="80" alt="GitHub">
</p>
```

---

## 2. Shields.io — badges

Formato: `https://img.shields.io/badge/TEXTO-COR?style=ESTILO&logo=LOGO&logoColor=white`

### Estilos

![flat](https://img.shields.io/badge/style-flat-3776AB?style=flat&logo=python&logoColor=white)
![flat-square](https://img.shields.io/badge/style-flat--square-3776AB?style=flat-square&logo=python&logoColor=white)
![plastic](https://img.shields.io/badge/style-plastic-3776AB?style=plastic&logo=python&logoColor=white)
![for-the-badge](https://img.shields.io/badge/style-for--the--badge-3776AB?style=for-the-badge&logo=python&logoColor=white)
![social](https://img.shields.io/badge/style-social-3776AB?style=social&logo=python)

### Tecnologias

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

![Stars](https://img.shields.io/github/stars/lianeheidemann/readme-components?style=flat-square)
![Forks](https://img.shields.io/github/forks/lianeheidemann/readme-components?style=flat-square)
![Último commit](https://img.shields.io/github/last-commit/lianeheidemann/readme-components?style=flat-square)
![Seguidores](https://img.shields.io/github/followers/lianeheidemann?style=social)

```md
![Stars](https://img.shields.io/github/stars/lianeheidemann/readme-components?style=flat-square)
![Forks](https://img.shields.io/github/forks/lianeheidemann/readme-components?style=flat-square)
![Licença](https://img.shields.io/github/license/lianeheidemann/readme-components?style=flat-square)
![Último commit](https://img.shields.io/github/last-commit/lianeheidemann/readme-components?style=flat-square)
![Seguidores](https://img.shields.io/github/followers/lianeheidemann?style=social)
```

> O badge de licença só aparece depois que o repositório tiver um arquivo `LICENSE`.

---

## 3. Skill Icons — vários ícones em uma linha

Formato: `https://skillicons.dev/icons?i=ICONE1,ICONE2,...`

![Skills](https://skillicons.dev/icons?i=js,ts,html,css,react,nodejs,python,git,docker,vscode)

```md
![Skills](https://skillicons.dev/icons?i=js,ts,html,css,react,nodejs,python,git,docker,vscode)
```

### Tema claro e ícones por linha

![Skills](https://skillicons.dev/icons?i=js,ts,react,python,git&theme=light&perline=5)

```md
![Skills](https://skillicons.dev/icons?i=js,ts,react,python,git&theme=light&perline=5)
```

---

## 4. Devicon — ícones individuais

Formato: `https://cdn.jsdelivr.net/gh/devicons/devicon/icons/NOME/NOME-original.svg`

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" alt="Python">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" alt="JavaScript">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="40" alt="React">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="40" alt="Node.js">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="40" alt="Git">
</p>

```html
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" alt="Python">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" alt="JavaScript">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="40" alt="React">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="40" alt="Node.js">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="40" alt="Git">
```

Variações: `-original`, `-plain`, `-line`, `-original-wordmark`, `-plain-wordmark`

---

## 5. Simple Icons — logos de marcas

Formato: `https://cdn.simpleicons.org/NOME/COR`

<p>
  <img src="https://cdn.simpleicons.org/github/white" width="32" alt="GitHub">
  <img src="https://cdn.simpleicons.org/python/3776AB" width="32" alt="Python">
  <img src="https://cdn.simpleicons.org/figma" width="32" alt="Figma">
  <img src="https://cdn.simpleicons.org/vercel/white" width="32" alt="Vercel">
</p>

```html
<img src="https://cdn.simpleicons.org/github/white" width="32" alt="GitHub">
<img src="https://cdn.simpleicons.org/python/3776AB" width="32" alt="Python">
<img src="https://cdn.simpleicons.org/figma" width="32" alt="Figma">
<img src="https://cdn.simpleicons.org/vercel/white" width="32" alt="Vercel">
```

---

## 6. GitHub Readme Stats — estatísticas do perfil

![Stats](https://github-readme-stats.vercel.app/api?username=lianeheidemann&show_icons=true&theme=tokyonight)

![Linguagens](https://github-readme-stats.vercel.app/api/top-langs/?username=lianeheidemann&layout=compact&theme=tokyonight)

```md
![Stats](https://github-readme-stats.vercel.app/api?username=lianeheidemann&show_icons=true&theme=tokyonight)
![Linguagens](https://github-readme-stats.vercel.app/api/top-langs/?username=lianeheidemann&layout=compact&theme=tokyonight)
```

Temas: `default`, `dark`, `radical`, `merko`, `gruvbox`, `tokyonight`, `onedark`, `dracula`

### Repositório fixado

![Repo](https://github-readme-stats.vercel.app/api/pin/?username=lianeheidemann&repo=readme-components&theme=tokyonight)

```md
![Repo](https://github-readme-stats.vercel.app/api/pin/?username=lianeheidemann&repo=readme-components&theme=tokyonight)
```

### Streak (sequência de contribuições)

![Streak](https://streak-stats.demolab.com?user=lianeheidemann&theme=tokyonight)

```md
![Streak](https://streak-stats.demolab.com?user=lianeheidemann&theme=tokyonight)
```

---

## 7. Typing SVG — texto animado

![Typing](https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&center=true&vCenter=true&width=500&lines=Olá,+eu+sou+a+Liane!;Bem-vindo+ao+meu+GitHub)

```md
![Typing](https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&center=true&vCenter=true&width=500&lines=Olá,+eu+sou+a+Liane!;Bem-vindo+ao+meu+GitHub)
```

Parâmetros: `font`, `size`, `color`, `center`, `width`, `lines` (separadas por `;`, espaços como `+`)

---

## 8. Contador de visitas

![Visitas](https://komarev.com/ghpvc/?username=lianeheidemann&color=blue&style=flat-square)

```md
![Visitas](https://komarev.com/ghpvc/?username=lianeheidemann&color=blue&style=flat-square)
```

---

## 9. Imagem diferente para tema claro e escuro

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/white">
  <source media="(prefers-color-scheme: light)" srcset="https://cdn.simpleicons.org/github/black">
  <img src="https://cdn.simpleicons.org/github/black" width="60" alt="GitHub">
</picture>

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/white">
  <source media="(prefers-color-scheme: light)" srcset="https://cdn.simpleicons.org/github/black">
  <img src="https://cdn.simpleicons.org/github/black" width="60" alt="GitHub">
</picture>
```

---

## 10. Dicas

- O GitHub remove JavaScript de SVGs; animações em CSS ou SMIL funcionam.
- Prefira `<img>` quando precisar controlar largura e altura.
- Sempre preencha o `alt` para acessibilidade.
- Serviços externos (stats, streak) às vezes ficam fora do ar; para algo crítico, salve o SVG no próprio repositório.
- Lista completa de ícones: skillicons.dev, devicon.dev e simpleicons.org.
  
