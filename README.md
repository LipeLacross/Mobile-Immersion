## 🌐 [English Version of README](README_EN.md)

# Mobile-Immersion

Food ordering app developed during Alura’s Mobile Immersion using Flutter. The project features category-based navigation, custom assets, ratings, and a modern UI to simulate a real food delivery experience.

- [Figma Design Prototype](https://www.figma.com/design/5WKjBnTvAKTraWTRqsjK02/TechTaste-%7C-Imers%C3%A3o?node-id=7-47&p=f)
- [Project IDX (Google Cloud IDE)](https://idx.google.com/)
- [Alura Imersão Mobile Guide](https://grupoalura.notion.site/Imers-o-Mobile-Guia-de-Mergulho-1ba379bdd09b80e3ac18c8512f31530d?pvs=4)

# TechTaste

Aplicativo de delivery de comida desenvolvido durante a Imersão Mobile da Alura, utilizando Flutter para criar uma experiência moderna, responsiva e multiplataforma. O projeto simula um marketplace de restaurantes, permitindo navegação por categorias, visualização de estabelecimentos, adição de pratos ao carrinho e checkout, com assets customizados e interface inspirada em grandes apps do mercado.

## 🔨 Funcionalidades do Projeto

- Splash screen personalizada
- Listagem de restaurantes com avaliações, distância e categorias
- Filtro e navegação por categorias de pratos (petiscos, principais, massas, sobremesas, bebidas)
- Visualização detalhada do restaurante e seus pratos
- Adição de pratos ao carrinho com controle de quantidade
- Checkout simples e visual moderno
- Interface responsiva baseada em Material Design
- Assets customizados para banners, ícones e imagens de pratos

### Exemplo Visual do Projeto

<table> <tr> <td align="center"> <img src="https://github.com/user-attachments/assets/e77be6d2-c164-4782-a0a1-dc08ac5d946e" width="120"/> </td> <td align="center"> <img src="https://github.com/user-attachments/assets/3e42d48c-ccef-42fa-aa0d-af71907e0842" width="120"/> </td> <td align="center"> <img src="https://github.com/user-attachments/assets/73aa3266-af74-4427-888e-742164ecd892" width="120"/> </td> </tr> <tr> <td align="center"> <img src="https://github.com/user-attachments/assets/7ee71d28-97eb-4c08-90f9-85688afe6c63" width="120"/> </td> <td align="center"> <img src="https://github.com/user-attachments/assets/48971992-0be3-4b7a-a957-bb7dc1bed4e8" width="120"/> </td> <td align="center"> <img src="https://github.com/user-attachments/assets/29e44c64-7b7e-4c35-893d-3ac5cd3577c0" width="120"/> </td> </tr> <tr> <td align="center"> <img src="https://github.com/user-attachments/assets/83bf845a-af88-410b-856d-cda6c215fe8c" width="120"/> </td> <td align="center"> <img src="https://github.com/user-attachments/assets/b15e5386-8c09-431d-afbb-4150b46694c1" width="120"/> </td> <td align="center"> <img src="https://github.com/user-attachments/assets/af369f8a-f964-4fe3-8f44-8a5ed1f79046" width="120"/> </td> </tr> </table> <div align="left">

- Veja o protótipo completo no [Figma](https://www.figma.com/design/5WKjBnTvAKTraWTRqsjK02/TechTaste-%7C-Imers%C3%A3o?node-id=7-47&p=f)

## ✔️ Técnicas e Tecnologias Utilizadas

- **Flutter** (framework multiplataforma)
- **Dart** (linguagem principal)
- **Provider** (gerenciamento de estado)
- **Material Design**
- **Assets locais** (imagens, ícones, dados em JSON)
- **Estrutura modularizada** (modelos, dados, UI)
- **Testes unitários básicos**
- **Project IDX** para desenvolvimento em nuvem (opcional, [saiba mais](https://idx.google.com/)[4][9])

## 📁 Estrutura do Projeto

- **lib/**
    - **data/**: Fontes e carregamento de dados (`categories_data.dart`, `restaurant_data.dart`)
    - **model/**: Modelos de domínio (`dish.dart`, `restaurant.dart`)
    - **ui/**: Interface do usuário, separada por telas e componentes
        - **_core/**: Temas, cores, provider do carrinho, widgets comuns
        - **home/**: Tela inicial e widgets
        - **restaurant/**: Tela de detalhes do restaurante
        - **splash/**: Splash screen
    - **main.dart**: Ponto de entrada da aplicação

- **assets/**
    - **banners/**: Imagens promocionais e splash
    - **categories/**: Ícones das categorias de pratos
    - **dishes/**: Imagens dos pratos
    - **restaurants/**: Imagens dos restaurantes
    - **others/**: Ícones auxiliares (estrela, bandeira de cartão)
    - **data.json**: Dados dos restaurantes

- **android/**, **ios/**, **web/**, **linux/**, **macos/**, **windows/**: Pastas de plataforma para build e configuração nativa

- **test/**: Testes unitários e de widget

- **pubspec.yaml**: Configurações do projeto e dependências

## 🛠️ Abrir e rodar o projeto

Para iniciar o projeto localmente, siga os passos abaixo:

1. **Certifique-se de que o Node.js está instalado** (para ferramentas auxiliares):
   ```bash
   node -v
   ```
   Se não estiver instalado, baixe em [nodejs.org](https://nodejs.org/).

2. **Clone o Repositório**:
   ```bash
   git clone 
   ```

3. **Instale as dependências do Flutter**:
   ```bash
   flutter pub get
   ```

4. **Rode o projeto**:
    - Para rodar em modo debug:
      ```bash
      flutter run
      ```
    - Para rodar no navegador:
      ```bash
      flutter run -d chrome
      ```
    - Para rodar em desktop:
      ```bash
      flutter run -d 
      ```

## 🌐 Deploy

- **Web**: Para gerar a versão web, utilize:
  ```bash
  flutter build web
  ```
  Os arquivos finais estarão em `build/web/`, prontos para deploy em qualquer serviço de hospedagem estática.

- **Android/iOS**: Utilize os comandos padrão do Flutter:
  ```bash
  flutter build apk   # Android
  flutter build ios   # iOS
  ```

- **Desktop**:
  ```bash
  flutter build windows
  flutter build macos
  flutter build linux
  ```

- **Project IDX**: Você pode usar o [Project IDX](https://idx.google.com/) para desenvolvimento em nuvem, com suporte a Flutter, preview web e Android, colaboração em tempo real, integração com Google Cloud e AI Gemini[4][7][9].

---

> **Referências e Guias**
>
> - [Guia oficial da Imersão Mobile - Alura](https://grupoalura.notion.site/Imers-o-Mobile-Guia-de-Mergulho-1ba379bdd09b80e3ac18c8512f31530d?pvs=4)
> - [Figma do projeto](https://www.figma.com/design/5WKjBnTvAKTraWTRqsjK02/TechTaste-%7C-Imers%C3%A3o?node-id=7-47&p=f)
> - [Project IDX (IDE Cloud Google)](https://idx.google.com/)
