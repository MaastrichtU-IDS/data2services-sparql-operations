pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git 'https://github.com/MaastrichtU-IDS/RdfUpload.git'
      }
    }
    stage('build') {
      steps {
        sh 'docker build -t rdf-upload .'
      }
    }
  }
}