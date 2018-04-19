#!groovy

// Example Jenkinsfile

node {
    stage('GIT') {
        checkout scm
    }
    stage('npm') {
        sh 'npm install'
    }
    stage('sonar') {
        sh 'npm run sonar'
    }
}
