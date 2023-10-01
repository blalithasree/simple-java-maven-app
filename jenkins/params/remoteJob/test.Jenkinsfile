pipeline{
    agent any
    stages{
        stage("Build another job with parameters"){
            steps{
                build wait: false, job: 'parameterisedpipeline', parameters: [string(name: 'choiceSelection', value: 'prod')]
            }
        }
    }
}