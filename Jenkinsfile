pipeline {
    agent any
    stages {
        stage ('Build') {
        steps {
            echo 'Running the Automated Job by Sergione'
            sh './gradlew build --no-daemon'
            archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
    }
}

}
