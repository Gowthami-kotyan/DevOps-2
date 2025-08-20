pipeline{
        agent any
        stages{
                stage('Checkout'){
                        steps{
                                git branch: 'main',url:
https://github.com/Gowthami-kotyan/dev-23.git
                        }
                }
                stage('Hello'){
                        steps{
                                echo "Hello from Jenkins Pipeline!"
                        }
                }
                stage('Goodbye'){
                        steps{
                                echo"Pipeline finished Succesfully"
                        }
                }
        }
}
