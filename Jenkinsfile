pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Init example'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
