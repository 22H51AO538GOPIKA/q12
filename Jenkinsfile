
pipeline{
  agent any
  stages{
    stage('build'){
      steps{
        script{
          bat 'docker build -t my-node-app .'
        }
      }
    }
    stage('test'){
      steps{
        script{
         echo 'running....'
        }
      }
    }
    stage('deploy'){
      steps{
        script{
          echo 'deploying..'
        }
      }
    }
  }
}
    
    
