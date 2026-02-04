pipeline {
    agent {
  node {
   label "linux && java11"
  }
 }
    stages {
        stage("Build") {
            steps {
                echo "Build....."
  echo "Build Success"
            }
        }
 stage("Test") {
            steps {
                echo "Test....."
  echo "Test Success"
            }
        }
        stage("Deploy") {
            steps {
                echo "Deploy....."
  echo "Deploy Success"
            }
        }


    }

    post {
      always {
 echo "I will always say Hello again!"
      }
      success {
 echo "Yay, success"
      }
      failure {
 echo "Oh no, failure"
      }
      cleanup {
 echo "Don't care succes or error"
      }
    }    
}
