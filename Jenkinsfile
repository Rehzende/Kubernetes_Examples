pipeline {
    agent {
        docker { image 'docker' }
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




