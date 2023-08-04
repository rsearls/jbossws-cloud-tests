
- build the project
        mvn clean package

- run the bootable jar
        mvn wildfly-jar:run -Dwildfly.bootable.run.jar.file.name=hello-0.0.1-SNAPSHOT-bootable-baremetal.jar

- test the rest app
        curl http://localhost:8080/hello
- test soap app
        curl http://localhost:8080/HelloWorld
