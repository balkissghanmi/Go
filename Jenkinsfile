pipeline {
  
    agent any
    
    stages {
        stage("go version") {
            steps {
                sh 'pwd'
                sh ' go build -buildvcs=false -o myapp'
            }
        }
    
    }
}
