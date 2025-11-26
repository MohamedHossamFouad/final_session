pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'Master', credentialsId: 'github', url: 'https://github.com/MohamedHossamFouad/final_session.git'
            }
        }
        stage('Run Script') {
            steps {
                sh 'bash test.sh'
            }
        }
    }
}
