pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        stage('test') {
            steps {
                echo 'completing build automation'
                echo 'completing build automation'
                echo 'completing build automation'
            }
        }
    }
}
