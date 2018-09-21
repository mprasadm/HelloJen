pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                withJava(java : 'maven_3_5_4') {
                    sh 'mvn package'
                }
            }
        }
	}
}