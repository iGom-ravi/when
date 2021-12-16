pipeline{
  agent any
  stages{
    stage("Build"){
      when {
        branch "master"
      }
      steps{
        echo "Building master"
    }
  }
    stage('Build Dev'){
      when{
        branch 'dev'
      }
      steps{
        echo 'Building dev'
      }
    }
}
