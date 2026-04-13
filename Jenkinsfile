pipeline{
    agent any
        stages{
            stage('code-checkout'){
                steps{
                    sh """
echo "Running ${env.BUILD_ID} " > file.txt
"""
                }
                }
        }
}
