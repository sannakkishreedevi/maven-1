pipeline {
    agent {
        label"java_node"
    }
    stages {
        stage('Checkout') {
            steps {
                git ''
            }
        }
         stage('Build') {
            steps {
              sh 'mvn clean package'
            }
        }
    }
}
    
  
        
     
