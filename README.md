# HOL Creando Microservicios con MicroProfile

== Requerimientos de sistema

Conexión a Internet es requerida para poder descargar dependencias de cada uno de los microservicios y para su posterior despliegue en la nube. Por favor instalar las siguientes herramientas para poder realizar el taller:

* Docker (https://docs.docker.com/docker-for-windows/install/[Windows], https://docs.docker.com/docker-for-mac/install/[Mac])
* Algún IDE Java (https://www.jetbrains.com/idea/download/[Intellij IDEA community], https://www.eclipse.org/downloads/packages/release/2019-06/r/eclipse-ide-enterprise-java-developers[Eclipse], https://netbeans.apache.org/download/nb110/nb110.html[Apache Netbeans])
* Algún JDK 8 (for example: https://adoptopenjdk.net/upstream.html/[OpenJDK], https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html[Oracle JDK], https://docs.aws.amazon.com/corretto/latest/corretto-8-ug/downloads-list.html[Amazon Corretto])
* https://maven.apache.org/download.cgi[Maven]
* https://git-scm.com/downloads[Git]
 
  
Una vez se han instalado las herramientas, es necesario descargar algunas imagenes de Docker y dependencias de Maven. Para ello ejecutamos los siguientes comandos:

1. docker pull mongo:3.6
2. git clone https://github.com/EventosJEspanol/latin-america-mp-hol.git
3. cd latin-america-micro-profile
4. mvn clean package
