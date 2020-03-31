pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
             echo 'Hello world'
            }
        }

        stage ('Testing Stage') {

            steps {
               echo 'Hello World'
            }
        }


        stage ('Deployment Stage') {
            steps {
                    echo 'mvn deploy'
            }
        }
    }
}
