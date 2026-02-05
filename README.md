# Links App

Este projeto é um aplicativo mobile desenvolvido em **React Native** seguindo um guia da Rocketseat. O objetivo do app é permitir que você armazene, categorize e gerencie links de forma simples e prática.

## Funcionalidades

- Adicionar novos links com nome, URL e categoria
- Categorizar links em: Curso, Projeto, Site, Artigo, Vídeo e Documentação
- Listar links filtrando por categoria
- Abrir links diretamente pelo app
- Excluir links salvos

## Tecnologias Utilizadas

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [AsyncStorage](https://react-native-async-storage.github.io/async-storage/) (armazenamento local)
- [Expo Router](https://expo.github.io/router/)
- [@expo/vector-icons](https://docs.expo.dev/guides/icons/)

## Como rodar o projeto

1. **Clone o repositório:**
   ```bash
   git clone <url-do-repo>
   cd links
   ```
2. **Instale as dependências:**
   ```bash
   npm install
   # ou
   yarn
   ```
3. **Inicie o projeto:**
   ```bash
   npx expo start
   ```
4. **Abra no seu dispositivo:**
   - Use o app Expo Go para escanear o QR Code exibido no terminal ou navegador.

## Personalização

- Você pode adicionar novas categorias editando o arquivo `src/utils/categories.ts`.
- Os links são armazenados localmente usando o AsyncStorage.

## Créditos

Projeto realizado com base no guia da [Rocketseat](https://rocketseat.com.br/).

---

Sinta-se à vontade para contribuir ou adaptar o app para suas necessidades!
