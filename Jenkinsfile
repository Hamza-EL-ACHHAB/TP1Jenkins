pipeline {
  
  agent any

  stages {

    stage("build"){
      steps{
        echo 'Building the application'
        adb devices start-server
      }
    }

    stage("test"){
      steps{
        echo 'Testing the application'
      }
    }

    stage("deploy"){
      steps{
        echo 'Deploying the application'
      }
    }

    
  }

  
}
