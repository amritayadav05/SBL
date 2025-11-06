pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        echo 'Compiling Java project......'
        bat 'javac HelloWorld.java'
      }
    }
     stage('test'){
      steps{
        echo 'Running the application......'
        bat 'javac HelloWorld'
      }
    }
     stage('Deploy'){
      steps{
        echo 'Deploying Java project......'
      }
    }
  }
}
