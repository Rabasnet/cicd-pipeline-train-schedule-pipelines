pipeline {
  agent any
    stages {
      stage ('build') {
        steps {
          echo "it is working till this part"
          sh './gradlew build --no-demon'
          archiveArtifacts artifacts 'dist/trainSchedule.zip'
        }
      }
    }
}
