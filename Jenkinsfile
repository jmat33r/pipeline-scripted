#!/usr/bin/env groovy
node {
    checkout scm
    stage('Build') {
        if ( env.BRANCH_NAME == 'development' ) {
            echo 'Building development'
        } else {
            echo 'Error'
        }
    }
    stage('Test') {
        echo 'Building....'
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}