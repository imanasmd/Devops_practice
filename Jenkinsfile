pipeline{
    agent any
        stages{
            stage('code-checkout'){
                steps{
                    sh 'cat ./html/index.html'
                        echo ${BUILD_ID}
                        echo ${env.JENKINS_URL}
                }
                }
        }
}
