pipeline {
    agent any

    stages {
        stage('git checkout scm') {
            steps {
		branches: [[name: 'main']],
   		userRemoteConfigs: [[url: 'https://github.com/angelbhagat/Practical.git']]

                echo 'Hello World1'
            }
        }
    }
}
