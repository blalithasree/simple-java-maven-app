pipeline{
    agent any
    stages{
        stage("Build another job with parameters"){
            steps{
                build job:'parameterisedpipeline' , parameters:[[$class:'checkboxParameter',name:'choiceSelection',value:'params.choiceSelection']]
            }
        }
    }
}