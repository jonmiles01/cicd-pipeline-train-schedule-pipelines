pipeline {
   agent any
  
  stages {
     stages ('Build') {
        steps {
           echo 'Running a build automation'
           sh './gradlew build --no-daemon'
           archiveArchitfacts artifacts: 'dist/trainschedule.zip'
        }
      }
  }
}
