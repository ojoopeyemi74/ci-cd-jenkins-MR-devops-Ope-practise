pipeline {
    agent any

    stages{

        stage ('Git checkout'){
            steps {
                script{
                    sh git branch: 'main', url: 'https://github.com/ojoopeyemi74/ci-cd-jenkins-MR-devops-Ope-practise.git'
                }
            }
        }
    }
}