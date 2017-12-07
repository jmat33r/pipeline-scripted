#!/usr/bin/env groovy
node {
    checkout scm

    def branches = sh(returnStdout: true, script: "git branch --contains ${commitId}")

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