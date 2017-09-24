pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World ich bin auf dem develop strang...'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
