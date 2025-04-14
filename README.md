# 🐦 Flappy Bird em Java

Uma recriação simples do clássico Flappy Bird usando **Java**, **Swing** e **AWT**. O projeto foi desenvolvido com fins educacionais e para fins de prática com interfaces gráficas em Java.

---

## 🎮 Demonstração

> Basta compilar e rodar o projeto! Use a tecla **Espaço** para fazer o pássaro voar. A pontuação aumenta conforme você passa pelos canos. Se bater, reinicia o jogo automaticamente.

---

## 🚀 Tecnologias utilizadas

- Java 8+
- Swing (interface gráfica)
- AWT (gráficos e eventos)
- Timer e KeyListener para lógica e controles

---

## 📁 Estrutura de Pastas

```
Flappy-Bird/
├── .vscode/
│   ├── settings.json               
├── bin/                   
│   ├── App.class
│   ├── FlappyBird.class
│   ├── FlappyBird$Bird.class
│   ├── FlappyBird$Pipe.class
│   ├── bottompipe.png
│   ├── flappybird.png
│   ├── flappybirdbg.png
│   ├── toppipe.png
├── lib/                   
├── src/                   
│   ├── App.java
│   ├── FlappyBird.java
│   ├── bottompipe.png
│   ├── flappybird.png
│   ├── flappybirdbg.png
│   ├── toppipe.png
```

---

## 🖼️ Recursos Visuais

As imagens usadas estão localizadas nas pastas `src/` e `bin/`, incluindo:

- `flappybird.png` (personagem principal)
- `flappybirdbg.png` (plano de fundo)
- `toppipe.png` e `bottompipe.png` (canos)
- Outros elementos gráficos para ambientação

---

## ⚙️ Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/matheuspeixotoo/flappy-bird-java
   ```

2. Compile os arquivos:
   ```bash
   javac -d bin src/*.java
   ```

3. Execute o jogo:
   ```bash
   java -cp bin App
   ```

> 📝 Certifique-se de estar com as imagens na mesma estrutura ao compilar e rodar, pois elas são carregadas via `getResource()`.

---

## 📌 Créditos

Desenvolvido por [Matheus Peixoto](https://github.com/matheuspeixotoo)

---

## 📜 Licença

Este projeto está licenciado sob a licença MIT. Sinta-se livre para usar, modificar e compartilhar!
