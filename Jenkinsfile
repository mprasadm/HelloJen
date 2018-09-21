pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                withJava(java : 'JAVA_SE_10_2') {
                    sh 'javac HelloJen.java'
                }
            }
        }
	}
}