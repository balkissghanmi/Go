pipeline {
  
    agent any
    
    stages {
        stage("go version") {
            steps {
                def goHome = tool name: 'go1.22.0', type: 'go'
                sh 'go version'
            }
        }
    
    }
}
