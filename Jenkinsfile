#!/usr/bin/env groovy
node {
    checkout scm

    

    stage('Build') {

        def branches = sh(returnStdout: true, script: "git branch --contains ${commitId}")
        
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