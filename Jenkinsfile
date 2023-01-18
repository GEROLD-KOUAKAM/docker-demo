pipeline {
     agent any
     stages {
         stage('Build image') {
             steps {
                  sh ' docker build -t geroldsiewe/docker-image . '
                }
             }
        }
   
    stages {
         stage('Build image') {
             steps {
                  sh ' docker push geroldsiewe/docker-image . '
                }
             }
        }
   
}



