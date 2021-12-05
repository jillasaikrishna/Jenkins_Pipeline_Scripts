pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                timeout(time:6,unit:'SECONDS'){
                    echo "sleeping in timeout"
                    sleep 2
                }
            }
        }

    }
}