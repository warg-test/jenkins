pipeline {
   agent any
  stages {
    stage ("Run script") {
      steps {
        input "Deploy to prod?"
        sh 'chmod +x conf.sh'
        sh './conf.sh'
      }
    }
  }
}
   
