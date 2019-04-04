## Relevant articles:

- [Microbenchmarking with Java](http://www.baeldung.com/java-microbenchmark-harness)

QuickStart

git clone https://github.com/eahumada/tutorials.git

sudo apt install maven
cd tutorials/jmh
mvn clean install 
	mvn -Dgib.enabled=false clean compile assembly:single install
ls target
java -jar target/jmh-1.0-SNAPSHOT-jar-with-dependencies.jar 

