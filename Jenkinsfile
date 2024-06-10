pipeline {
    agent any 
        stages {
            stage ('Make folders and files') {
                steps { 
                    bat "echo 'echo  hello' >  ~/script.bat"
                }
            }
            // stage ('View') {
            //     steps {  
            //         bat "echo ~/script2.bat"
            //     }
            // }
            stage ('Run') {
                steps {
                    bat "script.bat"
                }
            }
        }
}