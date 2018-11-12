pipeline{
    agent any
    tools {nodejs "node"}
    stages {
        stage('Build Clinicalaide'){
            steps{
                echo "Building clincial aide applciation"             
                bat 'npm install'
                bat 'npm run build'
            }
    }

       stage('Test Clinicalaide - Karma test cases'){
            steps{     
                echo "Testing clincial aide applciation"                                            
                bat 'npm run test'
            }
    }
}
}
