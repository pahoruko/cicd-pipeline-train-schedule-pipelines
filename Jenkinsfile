pipeline{
    agent any
  stages{
    stage {'Build'} {
      steps {
          echo 'Runbuild automoation'
          sh './gradlew build --no-daemon'
          archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }    
    }
  }    
}
