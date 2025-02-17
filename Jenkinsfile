pipeline {
    agent any
    stages {
        stage('NPM Install') {
            steps {
               bat 'npm install'
            }
        }
        stage('Ru ingration tests') {
            steps {
               bat 'npm run test'
            }
        }
    }

}
