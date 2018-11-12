pipeline{
    agent any  
    stages {
        stage('Build Clinicalaide'){
            steps{
                echo "Building clincial aide applciation"             
                bat 'node -v'               
            }
    }

       stage('Test Clinicalaide - Karma test cases'){
            steps{     
                echo "Testing clincial aide applciation"                                           
               
            }
    }
}
}
