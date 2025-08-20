pipeline{
 agent any
 stages{
   stage('Checkout'){
     steps{
        git branch: 'master', url:
'git@github.com:Gowthami-kotyan/new-1.git'
   }
  }
  stage('Hello'){
    steps{
      echo "hello from Jenkins Pipeline!"
     }
   }
  stage('Goodbye'){
    steps{
      echo "Pipeline finished sucessfully"
       }
     }
    }
   }
