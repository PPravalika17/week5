pipeline{
  agent any
  stages{
    stage('build'){
      steps{
        bat 'echo "Building Phase" '
        bat 'javac hello.java'
        bat 'java hello'
      }
    }
  }
}
