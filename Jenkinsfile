#!/usr/bin/env groovy
node {
    checkout scm
    stage('Build') {

        sh 'printenv'

        if ( $BRANCH == 'origin/development' ) {
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