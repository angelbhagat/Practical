pipeline {
    agent any

    stages {
        stage('git checkout scm') {
            steps {
		checkout changelog: false, poll: false, scm: scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/angelbhagat/Practical.git']])
                echo 'Hello World1'
            }
        }
    }
}
