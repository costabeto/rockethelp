# Rockethelp

Projeto desenvolvida durante o evento Ignite Lab - ReactNative da [Rocketseat](https://rocketseat.com.br)

![Image](https://raw.githubusercontent.com/costabeto/rockethelp/master/src/assets/ignite-lab-react-native.gif)

## A solução

Este projeto é uma aplicação desenvolvida em ReactNative com o objetivo de gerenciar solicitações de suporte em tempo real.

## Objetivo

Este projeto busca exercitar conceitos básicos de ReactNative, assim como boas práticas e tendências do ecossistema, alguns deles são:

- Expo Bare Workflow
- Estilização com NativeBase
- Projeto com Typescript
- Integração com Firebase
- Armazenamento com Cloud Firestore
- Autenticação com Firebase Authentication

## Requisitos para executar o projeto

- [NodeJS](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/) (Opcional)
- [Expo-CLI](https://docs.expo.dev/)
- [App Expo Go](https://expo.dev/client) (Opcional)

## Configurações

Algumas configurações são necessárias para executar devidamente o projeto, basicamente são duas:

- Simulador / Dispositivo
- Firebase

### Configurando Simulador / Dispositivo

Caso queira utilizar um dispositivo físico, Android ou IOS para executar o projeto, apenas instale a aplicação Expo GO e _certifique-se que está conectado na mesma rede do seu computador_.

Caso prefira utilizar um simulador para executar o projeto, pode utilizar qualquer um da sua preferência, mas é indicado que utilize um destes:

- [Simulador Android com Android Studio](https://developer.android.com/studio)
- [Simuador IOS com XCode](https://developer.apple.com/xcode/) (Apenas para MacOs)

### Configurando Firebase

Para configurar o Firebase do projeto é necessário criar uma conta na plataforma [Firebase](https://firebase.google.com/) e seguir os seguintes passos:

- Criar um novo projeto
- Criar um novo banco de dados Cloud Firestore
- Realizar configuração básica da Autenticação na plataforma Firebase

### Arquivos de configuração do Firebase

Para que a integração com o Firebase possa ser realizada com sucesso, primeiro, é necessário registrar uma nova aplicação no seu projeto, na página principal do Firebase

Ao adicinar uma nova aplicação, Android ou IOS, poderá baixar o arquivo `google-services.json` para Android ou `GoogleService-Info.plist` para IOS.

Após baixar o(s) arquivos, mova para a pasta raiz do projeto.

## Executando o projeto

- Clone o repositório para seu computdor com `git clone git@github.com:costabeto/rockethelp.git`
- No diretório do projeto, instale as dependências com `yarn` ou `npm install`
- Execute o projeto com `expo run:ios` ou `expo run:android`
