# 👋 Olá, eu sou DanielAlexandre-Dev

Um estudante de **Análise e Desenvolvimento de Sistemas**, desenvolvendo projetos em **Python**, **JavaScript** e aprendendo **TypeScript**. Estudo inglês nível básico e estou cursando faculdade na **UNIT**.

---

### 🟡 Pac‑Man Animado (gráfico exclusivo)
*Visual único, minimalista e realmente animado dentro do README*

```html
<!-- Pac-Man Animado para README -->
<svg width="300" height="80" viewBox="0 0 300 80" xmlns="http://www.w3.org/2000/svg">
  <!-- fundo opcional -->
  <rect width="300" height="80" fill="#0d1117" rx="8"></rect>

  <!-- Pellets -->
  <g fill="#ffd54a">
    <circle cx="80" cy="40" r="5"/>
    <circle cx="130" cy="40" r="5"/>
    <circle cx="180" cy="40" r="5"/>
    <circle cx="230" cy="40" r="5"/>
  </g>

  <!-- Pac-Man -->
  <g>
    <circle id="pac" cx="0" cy="40" r="18" fill="#ffe600" />

    <!-- Boca -->
    <polygon id="mouth" points="0,40 18,28 18,52" fill="#0d1117" />

    <!-- Animação de movimento -->
    <animateTransform
      xlink:href="#pac"
      attributeName="transform"
      attributeType="XML"
      type="translate"
      from="0 0" to="260 0"
      dur="3s"
      repeatCount="indefinite" />

    <animateTransform
      xlink:href="#mouth"
      attributeName="transform"
      attributeType="XML"
      type="translate"
      from="0 0" to="260 0"
      dur="3s"
      repeatCount="indefinite" />

    <!-- Animação boca abrindo/fechando -->
    <animate
      xlink:href="#mouth"
      attributeName="points"
      dur="0.35s"
      repeatCount="indefinite"
      values="0,40 18,28 18,52; 0,40 5,38 5,42; 0,40 18,28 18,52" />
  </g>
</svg>
```

---

### 🔗 Onde me encontrar
- **LinkedIn:** [Clique aqui](https://www.linkedin.com)
- **GitHub:** [DanielAlexandre-Dev](https://github.com/DanielAlexandre-Dev)

---

### 🚀 Tech Stack
- **Python**
- **JavaScript**
- **TypeScript** (estudando)
- **HTML & CSS**

---

### 📌 Sobre mim
Apaixonado por aprender, criar projetos e evoluir como desenvolvedor. Buscando oportunidades para entrar no mercado de tecnologia.

---
