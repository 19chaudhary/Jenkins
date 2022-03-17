pipeline { 
    agent any
    stages {
        stage('Clone Git') {
            steps {
                git 'https://github.com/19chauhdary/Jenkins.git'
            }
        }
        stage('Build Code') {
            steps {
              sh "pyhton3 Prog1.py"  
            }
        }
     stage('Test Code') {
            steps {
                sh "python3 Test.py"
            }
        }
    } 
}
