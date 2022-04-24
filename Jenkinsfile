pipeline{
  agent any
  stages{
    stage('Testing'){
      steps{
        echo 'running Tests'
    }
   }
   stage('Build'){
   steps{
   echo 'Building jar files...'
     sh 'python3 pratice.py'
   }
  }
 }
}
