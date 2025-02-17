pipeline {
    agent any
    stages {
        stage('NPM Install') {
            steps {
               bat 'npm install'
            }
        }
        stage('Run npm audit tests') {
        steps {
            bat 'npm audit'
        }
        }
        stage('Run ingration tests') {
            steps {
               bat 'npm run test'
            }
        }
         stage('Dobre si Nasko') {
            steps {
               echo 'Dobre si Nasko'
            }
        }
    }

}
