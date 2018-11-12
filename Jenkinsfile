pipeline{
    agent any  
    stages {
        stage('Build Clinicalaide'){
            steps{
                echo "Building suya3"             
                bat 'node -v'
                bat 'npm run ionic build'
            }
    }

       stage('Test Clinicalaide - Karma test cases'){
            steps{     
                echo "Testing clincial aide applciation"                                           
               
            }
    }
}
}
