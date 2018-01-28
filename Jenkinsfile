#!/usr/bin/env groovy
node {
    checkout scm
    stage('Build') {

        sh 'printenv'

        echo ${BRANCH_NAME}
       
    }
    stage('Test') {
        echo 'Building....'
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}


