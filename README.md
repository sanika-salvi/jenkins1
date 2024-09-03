# jenkins1

pipeline{
  agent any

  stages{
    stage('Build'){
      steps{
        bat 'javac Hello1.java'
      }
    }
    stage('Run'){
      steps{
        bat 'javac Hello1'
      }
    }
  }
}
