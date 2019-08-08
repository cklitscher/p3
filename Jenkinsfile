// Declarative //
pipeline {
  agent any
  stages {
  stage('Build') {
  steps {
  echo 'Building..'
  }
  }
  stage('Test') {
  steps {
  echo 'Testing..'
  }
  }
  stage('Deploy') {
  steps {
  echo 'Deploying....'
  }
  }
  }
}
// Script //
node {
  stage('Build') {
  echo 'Building2....'
  }
  stage('Test') {
  echo 'Building2....'
  }
  stage('Deploy') {
  echo 'Deploying2....'
  }
}
