pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/learnasws16161616/maven.git' // test change
            }
        }
         stage('Build') {
            steps {
              sh 'mvn clean package'
            }
        }
    }
}
    
  
        
     
