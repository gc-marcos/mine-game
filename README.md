# 💣 Mine Game

Um jogo estilo **Campo Minado** desenvolvido em **React Native**, com foco em experiência mobile fluida e intuitiva. O objetivo é encontrar todas as minas no tabuleiro sem explodir nenhuma!

![home_screen](https://github.com/user-attachments/assets/bd6d9558-40c2-48c7-8596-066c6cf4315e)
![hard_level_screen](https://github.com/user-attachments/assets/e2cfa96b-f534-4365-88e3-99be2be96465)
![game_over_screen](https://github.com/user-attachments/assets/a982021c-b8f9-485c-afa2-d31654c73f1d)

---

## 🎮 Demonstração

[mine_game.webm](https://github.com/user-attachments/assets/0e4ee9d3-7972-4d5f-9e07-6f11bd9ebfbf)

---

## 📱 Funcionalidades

* Geração dinâmica do tabuleiro;
* Sistema de contagem de minas restantes;
* Explosão ao tocar em uma mina;
* Botão **Novo Jogo** para reiniciar a partida;
* Dificuldades ajustáveis (futuramente).

---

## 🛠️ Tecnologias

* **React Native**
* **JavaScript**
* **Estilização com StyleSheet**
* Componentização e reaproveitamento de código

---

## 🚀 Instalação e Execução

```bash
# Clone o repositório
git clone https://github.com/gc-marcos/mine-game.git

# Acesse a pasta
cd mine-game

# Instale as dependências
npm install

# Execute o app (emulador Android ou dispositivo)
npx react-native run-android
```

---

## 📂 Estrutura do Projeto

```
mine-game/
├── src/
│   ├── components/
│   │   ├── MineField.js
│   │   └── Header.js
│   ├── screens/
│   │   └── LevelSelection.js
│   ├── params.js
│   └── functions/
│       └── gameLogic.js
├── App.js
└── README.md
```

---

## 🧠 Lógica do Jogo

* O tabuleiro é gerado com um número aleatório de minas baseado na dificuldade.
* Cada célula pode ser:

  * Vazia
  * Vizinha de uma ou mais minas (com número)
  * Mina (💣)
* O jogo termina ao abrir uma mina (com destaque em vermelho).
* A quantidade de minas restantes é atualizada no topo da tela.

---

## 📸 Screenshots

| Tela Inicial                        | Com 94 minas                        | Game Over                               |
| ----------------------------------- | ----------------------------------- | --------------------------------------- |
| ![home_screen](https://github.com/user-attachments/assets/ea6ed1fc-2ddb-49c8-ba19-3148407141d4) | ![hard_level_screen](https://github.com/user-attachments/assets/6d5bd959-132c-4fec-9fc6-45fcc8ff0b0f) | ![game_over_screen](https://github.com/user-attachments/assets/2635264f-9da8-46f2-8f26-a27cc8e1f379) |

---

## 💡 Próximos Passos

* Escolha de níveis de dificuldade
* Temporizador
* Modo escuro
* Suporte a iOS

---

## 👨‍💻 Autor

Desenvolvido por **[Marcos Carvalho](https://github.com/gc-marcos)**
Estudante de Informática para Negócios, apaixonado por soluções tecnológicas com impacto real.

---
