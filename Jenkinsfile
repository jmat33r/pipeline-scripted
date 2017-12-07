#!/usr/bin/env groovy
node {
    checkout scm

    def scmVars = checkout scm
    def branchName = scmVars.GIT_BRANCH

    stage('Build') {


        sh 'printenv'

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