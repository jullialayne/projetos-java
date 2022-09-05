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
