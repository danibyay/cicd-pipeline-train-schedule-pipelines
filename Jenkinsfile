pipeline {
    agent none 
    stages {
        stage('build') {
            agent {
                docker 'danibish/my-slave-nexus:latest'
            }   
            steps {
                sh './gradlew build --no-daemon'
            }
    }
}
}
