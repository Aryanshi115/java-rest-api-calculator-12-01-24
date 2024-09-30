pipeline {
  agent any
  stages {
    stage('login') {
      steps {
        sh '''docker logout
echo  tcgpass1 | docker login https://irepo.tcgdigital.com -utcgadmin --password-stdin'''
      }
    }

  }
}