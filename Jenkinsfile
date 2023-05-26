pipeline {
    agent {
        label"java_node"
    }
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/sannakkishreedevi/maven-1.git'
            }
        }
         stage('Build') {
            steps {
              sh 'mvn clean package'
            }
        }
    }
}
    
  
        
     
