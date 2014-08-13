Movie manager
=============

This is a demo project illustrating the use of standard Java EE front-end and back-end technologies.

Installation
------------

```sh
$ git clone https://github.com/miladhub/movie-manager.git movie
$ cd movie
$ mvn clean install
...
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 5.659 s
[INFO] Finished at: 2014-07-28T18:20:59+02:00
[INFO] Final Memory: 19M/491M
[INFO] ------------------------------------------------------------------------
$ cp target/movie.war ~/wildfly-8.1.0.Final/standalone/deployments
$ ~/wildfly-8.1.0.Final/bin/standalone.sh
```

The WAR has been successfully deployed on [JBoss WildFly](http://wildfly.org/downloads/). It doesn't need any specific configuration, just drop the WAR on the `standalone/deployments` folder and access the web app at [http://localhost:8080/movie/search.jsf](http://localhost:8080/movie).
