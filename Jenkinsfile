pipeline{
  agent any
  stages{
    stage("Build master"){
      when {
        changeRequest()
      }
      steps{
        echo "Building master"
    }
  }
  }  
}
