pipeline{
    agent any  
    stages {
        stage('Build Clinicalaide'){
            steps{
                echo "Building suya"             
                bat 'node -v'
                bat 'ionic -v'
            }
    }

       stage('Test Clinicalaide - Karma test cases'){
            steps{     
                echo "Testing clincial aide applciation"                                           
               
            }
    }
}
}
