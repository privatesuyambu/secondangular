pipeline{
    agent any  
    environment{
        PATH='/Users/Stephan/AppData/Roaming/npm'
    }
    stages {
        stage('Build Clinicalaide'){
            steps{
                echo "Building suya3"             
                bat 'node -v'
                bat 'ionic build'
            }
    }

       stage('Test Clinicalaide - Karma test cases'){
            steps{     
                echo "Testing clincial aide applciation"                                           
               
            }
    }
}
}
