pipeline{
    agent any  
    stages {
        stage('Build Clinicalaide'){
            steps{
                echo "Building suya2"             
                bat 'node -v'
                bat 'npm run ionic -v'
            }
    }

       stage('Test Clinicalaide - Karma test cases'){
            steps{     
                echo "Testing clincial aide applciation"                                           
               
            }
    }
}
}
