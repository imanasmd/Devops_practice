pipeline{
    agent any
        stages{
            stage('code-checkout'){
                steps{
                    sh 'echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}" > file.txt'
                }
                }
        }
}
