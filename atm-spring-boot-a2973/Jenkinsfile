pipeline{
    agent any

        tools {
            maven 'MAVEN_HOME'
        }

    stages{
        stage('Compile'){

            steps{
                  sh 'Hello from pipeline demo'
                  build 'atm-spring-boot-a2973'
            }
        }
    }
}

