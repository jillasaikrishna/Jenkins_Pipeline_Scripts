pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                timeout(time:4,unit:'SECONDS'){
                    echo "sleeping in timeout"
                    sleep 2
                }
            }
        }

    }
}