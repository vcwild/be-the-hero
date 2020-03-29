<p align="center">
  <img  src="https://github.com/vcwild/be-the-hero/blob/master/frontend/src/assets/logo.svg">
</p>

# Semana OmniStack 11
> Estudo baseado nas bilbiotecas React/React Native, utilizado para desenvolver a aplicação **Be The Hero**. Permite que ONGs possam cadastrar casos a partir da WEB, solicitando ajuda em ocorrências a serem atendidas pelo público em geral, através do app mobile.


#### Configurando o ambiente de desenvolvimento com:
- Node.js & npm;
- IDE VSCode c/ Add-ons: colorize; Dracula Official; Material Icon Theme; Node Exec.

### Back-End
#### Bibliotecas Utilizadas
- Express  -  Micro Framework para rotas;
- Nodemon -D  -  Atualiza em tempo real a aplicação back-end, no ambiente de desenvolvimento.

#### Resposta Visual para o Back-End
- Insomnia.

#### Banco de Dados
- SQLite.

#### Query Builder para db em SQL
- Knex.js  -  Construtor de dados;
- Driver  -   sqlite3.

#### Módulo de segurança
- Cors.

#### Principais Comandos:
- Iniciar o node package manager/Criar o package.json na pasta destino: 
`npm init -y`
- Instalar framework express no nodejs e acrescentar ao package automaticamente: 
`npm install express --save`
- Iniciar node package execute (npx) (executar container do nodejs): 
`npx create-react-app <appName>`
- Executa um pacote knex e cria um arquivo knexfile.js (nele que fica as configurações de acesso ao banco de dados):
`npx knex init`
- Controlador de segurança Cors: 
`npm install cors` 


### Front-End  |  ReactJS
#### Bibliotecas utilizadas
- react-router-dom  - rotas nativas do React;
- react-icons - estilização do conteúdo;
- axios - cliente http back-end.

### Mobile  |  React Native
#### Bibliotecas Utilizadas
- expo-cli;
- @react-navigation/native;
- react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view;
- @react-navigation/stack;
- expo-constants;
- @expo/vector-icons;
- expo-mail-composer;
- axios;
- intl.

#### Principais Comandos
- Instalar pacote expo de forma global (em toda a máquina): 
`npm install -g expo-cli`
- Iniciar o projeto: 
`expo init <projName>; expo init mobile; (project template: expo-template-blank)`
- Instalar navigation do React Native: 
`npm install @react-navigation/native`
- Instalar dependencias Expo managed: 
`expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view` 
- Instalar navegaçao no app por stack: 
`npm install @react-navigation/stack`
- Instalar módulo constants: 
`expo install expo-constants`
- Pacote expo para e-mail: 
`expo install expo-mail-composer`
- Pacote axios http para back-end: 
`npm install axios`
- Instalar pacote Intl: 
`npm install intl`

### Validação de Dados
#### Bibliotecas Utilizadas
- Celebrate: 
`npm install celebrate`

#### Próximos Passos:
- ESLint;
- Prettier;
- Autenticação JWT;
- Styled Components (React e React Native).
<p align="right">
  <img  width=200 hight=250 src="https://raw.githubusercontent.com/vcwild/be-the-hero/master/frontend/src/assets/heroes.png">
</p>
