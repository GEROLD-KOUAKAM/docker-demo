@Library('share-library')_
pipeline {
     agent none
     stages {
         stage('Build image') {
             agent any
             steps {
                script {
                  sh 'docker build -t geroldsiewe/docker-image .'
                }
             }
             }
        }
     }


