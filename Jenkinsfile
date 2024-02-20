pipeline {
  
    agent any
    tools{
        go 'go1.22.0'
    }
    stages {
        stage("go version") {
            steps {
                sh 'pwd'
                sh ' go version'
            }
        }
    
    }
}
