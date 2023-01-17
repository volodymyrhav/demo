pipeline {
    agent any
    environment{
      FLUTTER_VERSION         = "2.2.2"
    }
    stages {
        stage('Analyze') {
            steps {
                sh '''
                    env
                '''
            }
        }
        stage('Test') {
            steps {
                sh '''
                    whoami
                '''
            }
        }   

    }
}
