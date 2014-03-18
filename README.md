jacoco-maven-example
====================

this is maven project, which creates jacoco.exec report file, which can be used by sonar-runner

to run:

mvn clean package

sonar-runner


the reason is quite simple, just wanted to created some jacoco.exec report files and then use sonar-runner instead of maven to load data to sonarQuebe


you have to fill the these 4 properties files  (including sample examples) 
sonar.host.url=http://sonar_url
sonar.jdbc.url=jdbc:mysql://sonar_url:3306/sonar?useUnicode=true&amp;characterEncoding=utf8
sonar.jdbc.username=sonar
sonar.jdbc.password=password
