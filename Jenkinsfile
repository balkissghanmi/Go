pipeline {
  
    agent any
    
    stages {
        stage("go version") {
            steps {
                sh 'pwd'
                sh 'sudo go build -buildvcs=false -o myapp'
            }
        }
    
    }
}
