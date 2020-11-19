pipeline {
    agent  {
        docker 'my-slave-nexus:latest'
    }  
    stages {
        stage('build') {
              
            steps {
                sh './gradlew build --no-daemon'
            }
    }
}
}
