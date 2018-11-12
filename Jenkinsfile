pipeline{
    agent any
    tools {nodejs "node"}
    stages {
        stage('Example'){
            steps{
                echo "running from jenkins file"
                bat 'node -v'               
                bat 'npm install'
                bat 'npm run build'
                bat 'ionic cordova build android'
            }
    }

   
}   
}
