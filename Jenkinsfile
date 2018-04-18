#!groovy

// Dumy Jenkinsfile

node {
    stage('GIT') {
        git url: 'https://github.com/pohhen/test.git', branch: 'js-test'
    }
    stage('npm') {
        sh 'npm install'
    }
    stage('sonar') {
        sh 'npm run sonar'
    }
}
