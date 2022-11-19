pipeline {
   agent {
      label "Lokesh"
   }
   stages {
       stage('Build Code') {
           steps {
               sh """
               echo "Building Artifact"
               """
           }
       }
      stage('Deploy Code') {
          steps {
               sh """
               echo "Deploying Code"
               """
          }
      }
   }
}
