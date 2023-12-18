pipeline {
    agent {
        label 'agent'
    }

    stages {
        stage('Get Code') {
            steps {
                checkout scm // git branch: 'main', url: 'https://github.com/Robert89111911/App_of_apps.git'
            }
        }
    }
}
