pipeline {
  agent any
  stages {

    stage('Get the code') {
      checkout scm
    }
      
    stage('Build new image') {
      build
    }
    
    stage('Test') {
      test
    }
    
    stage('Deploy') {
      deploy
    }
    
  }
}
