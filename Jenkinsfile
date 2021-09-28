pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                withAnt( installation: ant){
                    echo "buld and compile"
                    sh "ant generate-ear"
                }
            }
        }
    }
}
