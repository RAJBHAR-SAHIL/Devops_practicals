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
                echo 'xcopy /s "*" "D:/Coding Software/xampp/htdocs/devops_xampp_jenkins/" /Y'
            }
        }

        stage('Print done'){
            steps{
                echo 'Done!'
            }
        }
    }
}
