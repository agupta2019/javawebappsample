import groovy.json.JsonSlurper

node {
  stage('init') {
    checkout scm
  }
  
  stage('build') {
    sh 'az ad sp list --show-mine '
  }  
}
