pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/MohamedHossamFouad/final_session.git'
            }
        }
        stage('Run Script') {
            steps {
                sh 'bash test.sh'
            }
        }
    }
}
