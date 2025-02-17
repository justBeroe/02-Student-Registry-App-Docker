pipeline {
    agent any
    stages {
        stage('NPM Install') {
            steps {
               bat 'npm install'
            }
        }
        stage('Run ingration tests') {
            steps {
               bat 'npm run test'
            }
        }
    }

}
