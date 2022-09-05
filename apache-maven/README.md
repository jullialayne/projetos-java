# APACHE-MAVEN

-Tenha um JDK instalado

-Baixe pacote apache:
https://maven.apache.org/download.cgi

-Descompacte o pacote maven e mova para uma pasta como C:/devtools

-Crie na Variável de Ambiente > Em Váriaveis de sistema > Editar Path > Adicionar diretório bin do Maven > Salve alterações

-Confira se o Maven foi instalado:
mvn -version

-Instancia Projeto Maven Básico
mvn archetype:generate -DgroupId=one.digitalinnovation -DartifactId=quick-start-maven -Darchetype=maven-archetype-quickstart -DinteractiveMode=false

#Comandos do dia a dia

1. Compilar:
mvn compile

2. Testar:
mvn test

3. Empacotar:
mvn package

4. Limpar diretório de trabalho:
mvn clean

# Buscar na internet modelos de projetos maven
maven archetype list
