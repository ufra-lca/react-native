# INSTRUÇÕES PARA USO
## PASSO 1 - Utilizando o Template
 
 - Para utilizar o template você deve clicar na opção "Use This Template". Isso irá redirecionar você para criar um novo reposotório já com o projeto todo configurado.
 
## PASSO 2 - Renomeando os Pacotes
 - Para renomear os pacotes para o nome do seu projeto, você deve utilizar o seguinte comando dentro da pasta do seu projeto "yarn global add react-native-rename". Após a execução, você pode renomear utilizando o seguinte comando react-native-rename "MeuProjeto" -b com.meuprojeto.

Link utilizado para renomear o pacote: https://www.npmjs.com/package/react-native-rename.

## PASSO 3 - Acesso ao ./gradlew

 - Antes de buildar o pacote você deve executar o seguinte comando dentro da pasta do seu projeto "chmod 755 android/gradlew
" para que não ocorra erro na hora de buildar seu projeto.
 
 Link utilizado para correção do erro: https://stackoverflow.com/questions/54541734/spawnsync-gradlew-eacces-error-when-running-react-native-project-on-emulator/55007109#55007109
