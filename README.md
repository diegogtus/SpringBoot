# SpringBoot

Cambios hechos

Proyecto 1:

Descargar ojdbc6 manual desde la pagina de oracle
Crear la carpeta /lib al mismo nivel de src
Agregar dentro de la carpeta /lib el ojbdc6-11.2.0.4.jar
Instalar el ojbdc6-11.2.0.4.jar de forma manual
    1. Abrir el cmd a nivel del pom.xlm del proyecto
    2. mvn install:install-file -DgroupId=com.oracle -DartifactId=ojdbc6 -Dversion=11.2.0.3 -Dpackaging=jar -Dfile=lib/ojdbc6.jar -DgeneratePom=true

 Agregar la siguiente configuracion al pom.xml
    					<configuration>
						<source>1.8</source>
						<target>1.8</target>
						<fork>true</fork>
					<executable>C:\Program Files\Java\jdk1.8.0_333\bin\javac</executable>
					</configuration>

Proyecto 2:

agregar mvn al incio del comando 
probando git-cafe
