pipeline {
   agent any
  stages {
    stage ("Run script") {
      steps {
        sh 'chmod +x conf.sh'
        sh './conf.sh'
      }
    }
     stage('Deploy approval'){
    input "Deploy to prod?"
}
  }
}
   
