pipeline {
  agent any

  stages {
    stage('install') {
      sh 'npm install'
    }
    stage('testing') {
      sh 'npm test'
    }
    stage('update web folder') {
      sh 'cp index.html /var/www/xsquad'
    }
  }
}
