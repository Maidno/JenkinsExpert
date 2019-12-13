pipeline {

    agent any

    stages{

        stage(Teste Unit){

            steps{

                echo 'Executando teste de unit'
                dir("$ExpertJenkins") {

                    sh '$ExpertJenkins/gradlew test'

                }

            }

        }

    }
}