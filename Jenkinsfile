#!/usr/bin/env groovy
node {
    
    def scmVars = checkout scm
    
    stage('Build') {

        shortCommit = sh(returnStdout: true, script: "git log -n 1 --pretty=format:'%h'").trim()

        echo 'shortCommit is: ' + shortCommit

        echo 'scmVars are: ' + scmVars

        def branchName = sh(returnStdout: true, script: 'git rev-parse --abbrev-ref HEAD').trim()
        echo 'branch name is: ' + branchName
        sh '#printenv'

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