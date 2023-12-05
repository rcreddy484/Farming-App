pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    // Clean and build the Android project
                    sh "./gradlew clean assembleDebug"
                }
            }
        }
        
    }
}
