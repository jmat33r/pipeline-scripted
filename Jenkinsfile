#!/usr/bin/env groovy
node {
    
    def scmVars = checkout scm
    
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