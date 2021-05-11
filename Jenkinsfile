pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building API'
        sh 'composer install'
      }
    }

    stage('Testing') {
      steps {
        echo 'Testing API'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

    stage('Sucess') {
      steps {
        echo 'Success'
      }
    }

  }
}