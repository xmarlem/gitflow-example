pipeline {
    agent any
    stages {
      stage('Preparation'){
        steps{
           git branch: 'develop', credentialsId: 'Github', url: 'https://github.com/xmarlem/gitflow-example.git'
           echo 'Hello World'
        }
      }
    }    
}
