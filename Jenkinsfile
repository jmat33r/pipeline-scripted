#!/usr/bin/env groovy
node {
    checkout scm
    stage('Build') {

        sh 'printenv'

        echo $GIT_BRANCH
       
    }
    stage('Test') {
        echo 'Building....'
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}


