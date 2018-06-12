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
            echo 'Msg1'
            echo 'Msg2'
        }
    }
}
