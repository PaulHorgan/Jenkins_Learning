pipeline {

    agent any 
        stages {
        stage ('Make folders and files') {
            steps { 
                bat '''
            mkdir testingPipeline
            echo "hi there" > testingPipeline\text.txt
        '''
            }
        }
        stage ('View') {
            steps {
                bat '''
                type testingPipeline\text.txt           
            '''               
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