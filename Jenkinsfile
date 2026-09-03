pipeline {
    agent any // Runs on any available executor node
 stages {
        stage('build') {
            steps {
               sh  'touch demo.py'
            }
        }
 }
 stages ('text'){
        stage('build') {
            steps {
               sh  'python3 text.py'
            }
        }
     
 }
}

