pipeline {
  agent { dockerfile true}
  stages {
    stage('Checkout SCM') {
            steps {
               git 'https://github.com/muzafferjoya/SF-Food-Truck.git'
            }
            
        }
    stage('Running Build') {
      steps {
        echo 'Successfully build the docker image and running this command inside it!'
      }
    }
  }
}
