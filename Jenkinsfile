@Library('my-shared-library')


pipeline{

    agent any

    stages{
        
        stage('Git Checkout'){

            steps{

                script{
                     
                    gitCheckout(
                        branch: "main",
                        url: "https://github.com/maheswar443/mrdevops_java_app.git"
                    )
                }
            }
        }
    }
}