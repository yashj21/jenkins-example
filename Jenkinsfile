pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
             echo 'Hello World'
            }
        }

        stage ('Testing Stage') {

            steps {
                withMaven(maven : 'maven_3_5_0') {
                   echo 'Here'
                }
            }
        }


        stage ('Deployment Stage') {
            steps {
                withMaven(maven : 'maven_3_5_0') {
                    echo 'mvn deploy'
                }
            }
        }
    }
}
