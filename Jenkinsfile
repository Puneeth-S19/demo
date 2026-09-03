pipeline {
    agent any // Runs on any available executor node
 stages {
        stage('build') {
            steps {
               sh  'touch demo.py'
            }
        }

        stage('test-ts') {
            steps {
               sh  'python3 text.py'
            }
        }
     
 }

}
