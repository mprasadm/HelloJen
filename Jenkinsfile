node {
    stage ('Clean') {    					
		bat "mvn clean"						
    }
	stage ('Compile') {    					
		bat "mvn compile"						
    }
	stage ('Build') {    					
		bat "mvn package"						
    }
	stage ('RUN') {    					
		bat "java -jar target/java-archive-1.0-SNAPSHOT.jar"						
    }
}
