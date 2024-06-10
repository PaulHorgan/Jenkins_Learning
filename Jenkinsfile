pipeline {
    agent any 
        stages {
            stage ('Make folders and files') {
                steps { 
                    bat "touch ~/script.bat"
                }
            }
            stage ('View') {
                steps {  
                    bat "touch ~/script2.bat"
                }
            }
            stage ('Run') {
                steps {
                    bat"'script.bat"
                }
            }
        }
}