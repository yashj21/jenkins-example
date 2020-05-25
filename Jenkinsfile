pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
             echo 'Helo world'
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
