pipeline {
    agent any

    stages {
        stage('Copy Script') {
            steps {
                // Adjust the path if the script is not in the same directory as Jenkinsfile
                sh 'cp /kp07.py .'
            }
        }

        stage('Run Python Script') {
            steps {
                sh 'python3 kp07.py'
            }
        }
    }
}
