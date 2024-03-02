pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
                'checkout scmGit(branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/rajesh212192/JavaWebCalculator.git']]
            }
            }
        stage('test') {
            steps {
                echo 'Running test automation'
                echo 'test success'
            }
            }
        stage('deploy') {
            steps {
                echo 'Running deploy automation'
                echo 'deploy success'
            }
            }
          
        }
}
