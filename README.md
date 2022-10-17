![Thumbnail](https://cdn.discordapp.com/attachments/743927816021737565/1031656604350816306/thumbnail-app-de-compras.png)

# 👨🏽‍💻 React Native: Meu Primeiro Projeto

Esse é o projeto desenvolvido no curso **Começando do Zero** da formação em **React Native** da [Alura Cursos](https://www.alura.com.br/).

## 📱 Projeto

Esse projeto implementa a tela de detalhes da cesta do e-commerce *orgs*. Nesta tela são mostrados dados estáticos do nome da cesta, fazenda, preço e itens da cesta.

<img src="https://user-images.githubusercontent.com/9091491/123982988-e3ccb700-d999-11eb-880e-872881ee8b10.gif" width="350" />

## 💻 Técnicas e Tecnologias

As técnicas e tecnologias que foram utilizadas no projeto foram:

- `Expo`: tecnologia para simplificar o ambiente de desenvolvimento. Através dela podemos visualizar em tempo real a aplicação no celular.
- `Componentes React Native`: componentes básicos já existentes da tecnologia que compõem a tela.
  - `Text`: componente básico para exibir textos.
  - `View`: container principal que abrange os outros componentes.
  - `ScrollView`: container para blocos de componentes com barra de rolagem.
  - `Image`: componente para exibição de imagens.
  - `TouchableOpacity`: componente para criar áreas clicáveis
- `Componentes customizados`: criação e utilização de componentes customizados
- `Suporte a telas`: não permitir que conteúdos estejam sob a *StatusBar* (barra superior nativa) ou barra de gestos do iPhone
- `Expo Google Fonts`: suporte a fontes do google via Expo
- `StyleSheet`: estilização básica de componentes
- `Dimensions`: captura de dados das dimenções da tela

## 📲 Executando o projeto

### ✔️ Pré-requisitos

Para conseguir rodar o projeto em sua máquina você pode precisará dos seguintes itens:
- NodeJS para podermos rodar `expo` e `npm`. Você pode instala-lo [aqui](https://nodejs.org/en/);
- Um celular Android ou iOS com o aplicativo Expo GO instalado, para que assim, você possa testar em seu dispositivo, ou então, algum simulador Android ou iOS no computador.

Se quiser testar as instalações, rodar os comandos abaixo separadamente deve mostrar as respectivas versões.

```
node --version
npm --version
```

Então com o `npm` instalado podemos instalar o `expo` e checar a versão:
```
npm install --global expo-cli
expo --version
```

### ▶ Rodando o Projeto

Agora que já tem a pasta do projeto na sua máquina, dentro dela instale as dependências:
```
npm install
```

Então podemos rodar o projeto:
```
npm start
```

Uma guia no navegador irá abrir, geralmente [neste endereço](http://localhost:19002/).
Caso estiver com o celular, **escaneie o QR code com o aplicativo do Expo** ou a câmera.
Se seu celular estiver em outra rede diferente do computador, troque a "CONNECTION" para "Tunnel", que o app será transmitido via internet.
Se tiver um simulador, clique na opção do sistema operacional do seu simulador no menu esquerdo.

Pronto, agora o app você deve ver o app rodando.
