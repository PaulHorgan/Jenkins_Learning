pipeline {

    agent any 
        stages {
        stage ('Make folders and files') {
            steps { 
                bat '''
            mkdir testingPipeline

        '''
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