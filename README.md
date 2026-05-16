[README.md](https://github.com/user-attachments/files/27854795/README.md)
# 🍎 Food Runner

> Corra, pule e colete comidas frescas — evite as estragadas!

Um jogo de corrida infinita no estilo do dinossauro do Chrome, feito com **HTML5 Canvas**, CSS puro e JavaScript vanilla. Sem frameworks, sem dependências.

---

## 🎮 Como Jogar

| Ação | Controle |
|---|---|
| Pular | `Espaço` ou `↑` |
| Pular (mobile) | Toque na tela |

- **Comidas frescas** 🍎🍕🍰🍇 → colete para ganhar **+10 pontos**
- **Comidas estragadas** ☠️🤢🦠 → evite ou perca uma vida
- Você tem **3 vidas** — use com sabedoria!
- A velocidade aumenta conforme a pontuação sobe

---

## 🚀 Como Rodar

### Opção 1 — Abrir direto no navegador

Basta clonar e abrir o `index.html`:

```bash
git clone https://github.com/seu-usuario/food-runner.git
cd food-runner
# Abra o index.html no seu navegador
```

### Opção 2 — Servidor local (recomendado)

```bash
# Com Python
python -m http.server 8080

# Com Node.js (npx)
npx serve .

# Com VS Code: instale a extensão Live Server e clique em "Go Live"
```

Acesse `http://localhost:8080` no navegador.

---

## 📁 Estrutura do Projeto

```
food-runner/
├── index.html          # Página principal com layout do site
├── css/
│   └── style.css       # Estilos do site e da tela de jogo
├── js/
│   └── game.js         # Lógica completa do jogo (Canvas)
└── README.md
```

---

## ✨ Funcionalidades

- 🏃 Personagem animado com pernas, braços e expressão facial
- ❤️ Sistema de 3 vidas com invencibilidade temporária após dano
- 💥 Partículas e textos flutuantes ao coletar/tomar dano
- ☁️ Nuvens animadas e cenário com paralaxe
- 🔥 Dificuldade progressiva — velocidade e frequência aumentam
- 🏆 Recorde salvo na sessão
- 📱 Compatível com mobile (touch)
- 🌐 Site completo com header, hero, seção de regras e rodapé

---

## 🛠️ Tecnologias

- **HTML5 Canvas** — renderização do jogo
- **CSS3** — layout responsivo, animações, glassmorphism
- **JavaScript ES6+** — lógica do jogo com IIFE para encapsulamento
- **Google Fonts** — Fredoka One + Nunito

---

## 🌐 Deploy no GitHub Pages

1. Vá em **Settings → Pages** no seu repositório
2. Em **Source**, selecione `main` e pasta `/ (root)`
3. Clique em **Save**
4. Seu jogo estará em: `https://seu-usuario.github.io/food-runner/`

---

## 📝 Licença

MIT — use, modifique e compartilhe à vontade!

---

Feito com ❤️ e muita comida boa 🍕
