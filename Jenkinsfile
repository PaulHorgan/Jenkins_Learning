pipeline {

    agent any 
        stages {
        stage ('Make folders and files') {
            steps { 
                
           sh "touch ~/script.bat"
            }
        }
        stage ('View') {
            steps {
              
            }
        }
        stage ('Run') {
            steps {
                bat 
                'script.bat'
            }
        }
    }
}