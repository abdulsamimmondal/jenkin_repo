
pipeline {

    agent any

    stages {

        stage('Clone Repository') {

            steps {

                git url:'https://github.com/abdulsamimmondal/jenkin_repo.git',branch:'main'

            }

        }

        stage('Build') {

            steps {

                sh 'echo "Building the application..."'

            }

        }

        stage('Test') {

            steps {

                sh 'echo "Running tests..."'

            }

        }

        stage('Deploy') {

            steps {

                sh 'echo "Deploying application..."'

            }

        }

    }

}

