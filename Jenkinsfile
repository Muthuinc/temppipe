pipeline {
    agent any
    environment {
        MUTHU = credentials('Demo-pass')
    }
    
    stages {
        stage ('checking password') {
            steps {
                sh """
                    ./build.sh
                    """
            }
        }
    }
}