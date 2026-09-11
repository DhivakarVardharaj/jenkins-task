pipeline {
    agent {label 'built-in'}
    stages {
        stage('Build') {
            steps {
              bat 'echo "Hello Dhivakar" > build.txt'
            }
        }

        stage('Archive') {
            steps {
               archiveArtifacts artifacts: 'build.txt'  
    }
}
    
    }

}
