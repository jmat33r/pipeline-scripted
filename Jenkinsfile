#!/usr/bin/env groovy
node {

    checkout scm

    stage('Build') {

        sh "echo ${env.BRANCH_NAME}"

        if ( 'development' == 'development' ) {
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

