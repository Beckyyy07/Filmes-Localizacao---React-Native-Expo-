# Aplicativo de Busca de Filmes com Exibição de Localização

Este é um aplicativo React Native que permite aos usuários buscar detalhes de filmes usando a API OMDB e exibir a localização atual do usuário em um mapa usando Expo Location e `react-native-maps`.

## Funcionalidades

- **Busca de Filmes**: Pesquise filmes por título e obtenha informações detalhadas, incluindo ano, gênero, diretor e prêmios.
- **Exibição de Localização**: Solicite e exiba a localização atual do usuário em um mapa, incluindo latitude e longitude.

## Instalação

### Pré-requisitos

- Node.js e npm instalados
- Expo CLI instalado globalmente (`npm install -g expo-cli`)

### Passos

1. Instale as dependências:
   ```sh
   npm install
   ```

2. Obtenha uma chave de API da OMDB

3. Inicie o servidor de desenvolvimento do Expo:
   ```sh
   expo start
   ```

## Uso

1. Execute o seguinte comando no terminal: "expo start" ou "npx expo start". Em seguida, leia o código QR com o Expo Go no seu dispositivo móvel ou você pode utilizar o Android Studio para executar o aplicativo em um emulador Android.
2. Insira um título de filme na barra de pesquisa e pressione "Buscar Filme" para buscar os detalhes do filme.
3. Permita permissões de localização quando solicitado para ver sua localização atual no mapa.
