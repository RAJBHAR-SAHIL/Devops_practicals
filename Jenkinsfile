pipeline {
    agent any
    stages{
        stage('checking python version') {
            steps {
                bat 'python -V'
            }
        }

        stage('REPO Cloning'){
            steps {
                git 'https://github.com/RAJBHAR-SAHIL/Devops_practicals.git'
            }
        }

        stage('Print done'){
            steps{
                echo 'Done!'
            }
        }
    }
}
