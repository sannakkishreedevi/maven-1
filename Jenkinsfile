pipeline {
    agent {
        label"java_node"
    }
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/learnasws16161616/maven.git'
            }
        }
         stage('Build') {
            steps {
              sh 'mvn clean package'
            }
        }
    }
}
    
  
        
     
