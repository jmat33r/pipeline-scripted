#!/usr/bin/env groovy
BNAME = env.BRANCH_NAME
node {
    checkout scm

    sh 'echo $BNAME'
    
    stage('Build') {
        echo 'Building....'
    }
    stage('Test') {
        echo 'Building....'
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}