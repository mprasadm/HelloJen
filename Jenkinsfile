pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                withMaven(maven : 'maven_3_5_4') {
					node {
						def status = powershell(returnStatus: true, script: 'mvn package')
						if (status == 0) {
							// Success!
						}
					}
                }
            }
        }
	}
}