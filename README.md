# Configura-es_de_ambiente_java
 - Totorial para configurar seu ambiente java

# Passo 1
  - Instalar o JDK do java.

# Passo 2
  - Se sua máquina for windows abra o menu variaveis de ambiente.
  - Em variaveis do sistema, clique em novo.
    - escreva JAVA_HOME, no cammpo valor da variavel, clique no botão procurar e ache a pasta do java
    - geralmente vai estar neste caminho C:\Program Files\Java\jdk-17.
    - depois clique em ok.
    - clique me novo novamente
    -  escreva JAVA_JRE, no cammpo valor da variavel, clique no botão procurar e ache a pasta do java
    -  geralmente vai estar neste caminho C:\Program Files\Java\jdk-17. (é a mesma configuração do JAVA_HOME isso partir da versão 10 do java)
    -  Depois devemos criar uma variavel chamada CLASSPATH, com este valor de variavel .;%JAVA_HOME%\lib, igual criamos a JAVA_HOME e JAVA_JRE.
    -  por fim devemos adicionar dois caminhos abrindo as configs do path.
    -  então adicionamos, um novo nesta lista, e escrevemos assim %JAVA_HOME%\bin.
    -  e para terminar colocamos o caminho do jdk C:\Program Files\Java\jdk-17, no path tbm.

# Passo 3
 - Configurando o eclipse de acordo com  a versão java que está instalado
  - Na IDE eclipse vá em Window -> Preference
  - No campo de busca digite JRE.
  - Depois verifique na opção installed JREs, se ele está apontando para o JDK correto.
  - Caso não esteja, remova. Vá em adicionar, depois standart VM, vai em diretorio.
  - coloque o caminho do seu JDK, geralmente será este C:\Program Files\Java\jdk-17.
  - Depois em windows -> preference, digite jre.
    - Vá em execution environments, escolha sua versão de instalação java
    - Caso não encontre escolha, a ultima versão mais próxima da sua, e no campo compatible JREs escolha a sua que está insatalada.

# Passo 4
- Verificar o JDK
- Na IDE eclipse vá em Window -> Preference
- No campo de busca digite JDK.
-  Verifique a versão do java no compiler.

# Passo 5
- Verificar o Build path
- Na IDE eclipse vá em Window -> Preference
- No campo de busca digite java.

# Passo 6
- Configurando o servidor TomCat na IDE.
- Windows -> showview - Others -> digiter server
- Seleciona serve e abre.
- Clique no link:
 - No servers are available. Click this link to create a new server...
- Selecione o a versão do tomcatch que está instalado na sua máquina, na guia apache. (Importante que o tomcatch esteja dentro do caminho c:, para ele funcionar corretamente).
- Depois seleciona o botão "next"
- na próxima tela escolha o diretório do seu tomcat e no campo JRE escolha o seu JRE baixado.
- Depois next e finhs.

# Passo 7
- Depois la em baixo na guia server.
- Clique no servidor configurado.
- Na opção server location coloque "Use tomcat Installation" (usar o tomcat instalado localmente).
- Depois vá no disket la em cima e salve está configuração.
 
