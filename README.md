# be-the-hero

<p align="left"
  <img  src="https://github.com/vcwild/be-the-hero/blob/master/frontend/src/assets/logo.svg">
</p>

# Semana OmniStack 11
> Curso de desenvolvimento em React/React Native da aplicação **Be The Hero**. Na qual ONGs poderao cadastrar casos a partir da WEB, solicitando ajuda em ocorrencias que podem ser atendidas através do app mobile pelo público em geral. O front-end, elaborado em React (web) e React Native (mobile), será integrado no back-end em Node.js. 

#### Configurando o ambiente de desenvolvimento com:
- Node.js & Gerenciador de pacotes npm
- IDE VSCode c/ Add-ons: colorize; Dracula Official; Material Icon Theme; Node Exec

### Back-End
#### Bibliotecas Utilizadas
- Express  -  Micro Framework para rotas
- Nodemon -D  -  Atualiza em tempo real a aplicação back-end, no ambiente de desenvolvimento
#### Resposta Visual para o Back-End
- Insomnia
#### Banco de Dados
- SQLite
#### Query Builder para db em SQL
- Knex.js  -  Construtor de dados
- Driver  -   sqlite3
- npx knex init - Com npx, ele executa um pacote knex. E cria um arquivo 
chamado knexfile.js (nele que fica as configurações de acesso ao banco de dados) 
#### Módulo de segurança
- npm install cors - Serve para dizer qual endereço (http | front-end) pode acessar o servidor
##### Principais Comandos:
- npm init -y // Iniciar o node package manager/Criar o package.json na pasta destino
- npm install express --save // Instalar framework express no nodejs e acrescentar ao package automaticamente
- npx create-react-app <appName> // Iniciar node package execute (npx) (executar container do nodejs)


### Front-End  |  ReactJS
#### Bibliotecas utilizadas
- react-router-dom  - rotas nativas do React
- react-icons - estilizaçao do conteúdo
- axios - cliente http backend

### Mobile  |  React Native
#### Bibliotecas Utilizadas
- expo-cli
- @react-navigation/native
- (expo install) react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view
- @react-navigation/stack
- (expo install) expo-constants
- @expo/vector-icons  - Nativa do Expo
- (expo install) expo-mail-composer
- axios
- intl
##### Principais Comandos
- npm install -g expo-cli // Instalar pacote expo de forma global (em toda a máquina)
- expo init <projName>; expo init mobile; (project template: expo-template-blank) // Iniciar o projeto
- npm install @react-navigation/native // Instalar navigation do React Native
- expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view // Instalar dependencias Expo managed
- npm install @react-navigation/stack // Instalar navigaçao por stack
- expo install expo-constants
- expo install expo-mail-composer // Pacote expo para e-mail;
- npm install axios // Pacote axios http para back-end
- npm install intl // Instalar pacote Intl

### Validaçao de Dados
#### Bibliotecas Utilizadas
- Celebrate
- npm install celebrate

<p align="right">
  <img  width=200 hight=250 src="https://raw.githubusercontent.com/vcwild/be-the-hero/master/frontend/src/assets/heroes.png">
</p>
