### Simple Spring Native poc

To start in command line:
```shell
  mvn clean spring-aot:generate spring-boot:run
```

or... just execute the shell file `start.sh`

This will start the application in port 8080.

Check if the hello world is working by consuming:
`curl http://localhost:8080/hello`



To build an image, there's a maven plugin provided by spring that also deals with
this.
``` mvn spring-boot:build-image```