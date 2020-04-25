pipeline {
    agent {
        docker { image 'docker:dind' }
    }
    stages {
         stage('Rancher Help') {
            agent {
                docker { image 'rehzende/rancherclik8s' }
            }
            steps {
                sh 'rancher --help'
            }
        }
    }
}




