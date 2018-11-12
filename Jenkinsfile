pipeline{
    agent any
    tools {nodejs "node"}
    stages {
        stage('Build Clinicalaide'){
            steps{
                echo "Building clincial aide applciation"             
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
