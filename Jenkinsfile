pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
               sh 'echo "Hello , From Dhivakar"' > build.txt
            }
        }

        stage('test') {
            steps {
                archiveArtifacts artifacts: 'build.txt' 
    }
}
    
    }
}
