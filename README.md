Meu Aplicativo de Mapas

Este é um aplicativo simples desenvolvido em React Native que exibe um mapa interativo com um marcador em uma localização específica.
Tecnologias Utilizadas

    React Native: Framework para construção de aplicativos móveis.
    react-native-maps: Biblioteca para integrar mapas no aplicativo.

Instalação

Para rodar este projeto, você precisará ter o Node.js e o React Native CLI instalados em seu ambiente. Siga os passos abaixo para configurar e executar o aplicativo:
1. Clone o Repositório

git clone https://github.com/RaissaMarques96/app-maps.git
cd seu_repositorio

2. Instale as Dependências

npm install

ou, se estiver usando Yarn:

bash

yarn install

3. Instale as Dependências do react-native-maps

Siga as instruções da documentação oficial do react-native-maps para instalar as dependências nativas, incluindo as configurações necessárias para iOS e Android.
4. Execute o Aplicativo

Para Android:
npx react-native run-android

Para iOS:

npx react-native run-ios

Funcionalidades

    Visualização de um mapa centrado em uma localização específica.
    Um marcador que representa um local (IFMA Timon) com um Callout que exibe informações adicionais.

Estrutura do Código

O código principal do aplicativo está no arquivo App.js. Aqui está um resumo da estrutura:

    Importações: Importa os componentes necessários do React Native e da biblioteca react-native-maps.
    Coordenadas: Define a latitude e longitude do marcador.
    Componente App: Renderiza a visualização do mapa e o marcador.
    Estilos: Estilos para o contêiner do mapa e o Callout.

![Screenshot_1727894220](https://github.com/user-attachments/assets/8a307e31-f49d-46b8-a4a7-8e46c9828d3f)

    
    

