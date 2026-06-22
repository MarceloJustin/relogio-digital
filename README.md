# Relógio Digital

![Java](https://img.shields.io/badge/Java-21-orange?style=flat-square&logo=openjdk)
![JavaFX](https://img.shields.io/badge/JavaFX-21.0.10-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

## 📌 Sobre o Projeto

Aplicação desktop desenvolvida com **JavaFX** que exibe um relógio digital com o horário atual do sistema, atualizado em tempo real a cada segundo. Projeto criado durante o aprendizado de JavaFX com foco em animações e atualização dinâmica de interface.

## 🚀 Tecnologias Utilizadas

- **Java 21**
- **JavaFX 21.0.10**
- **Eclipse IDE**

## 🏗️ Estrutura do Projeto

```
src/
└── application/
    ├── Main.java          # Classe principal da aplicação JavaFX
    └── application.css    # Arquivo de estilos (CSS JavaFX)
```

## 📋 Funcionalidades

- Exibe o horário atual no formato `HH:mm:ss`
- Atualização automática a cada segundo via `Timeline` com `KeyFrame`
- Interface minimalista: fundo preto, texto amarelo em fonte de 30pt
- Janela de 300×100 pixels centralizada

## ▶️ Como Executar

### Pré-requisitos

- [JDK 21](https://www.oracle.com/java/technologies/downloads/#java21)
- [JavaFX SDK 21.0.10](https://gluonhq.com/products/javafx/)

### Pelo Eclipse IDE

1. Clone o repositório:
   ```bash
   git clone https://github.com/MarceloJustin/RelogioDigital.git
   ```
2. Abra o Eclipse e importe o projeto: **File → Import → Existing Projects into Workspace**
3. Configure o JavaFX SDK nas propriedades do projeto em **Build Path → Libraries**, apontando para a pasta `lib` do seu JavaFX SDK
4. Execute a classe `application.Main` como **Java Application**

### Pela linha de comando

```bash
# Compile
javac --module-path /caminho/para/javafx-sdk-21.0.10/lib \
      --add-modules javafx.controls,javafx.fxml \
      -d bin src/application/Main.java

# Execute
java --module-path /caminho/para/javafx-sdk-21.0.10/lib \
     --add-modules javafx.controls,javafx.fxml \
     -cp bin application.Main
```

> Substitua `/caminho/para/javafx-sdk-21.0.10/lib` pelo caminho real do JavaFX SDK na sua máquina.

## 👨‍💻 Autor

**Marcelo Justin**

[![GitHub](https://img.shields.io/badge/GitHub-MarceloJustin-181717?style=flat-square&logo=github)](https://github.com/MarceloJustin)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-marcelojustin-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/marcelojustin)

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
