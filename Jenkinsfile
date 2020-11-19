pipeline {
    agent  {
        docker 'danibish/my-slave-nexus:latest'
    }  
    stages {
        stage('build') {
              
            steps {
                sh './gradlew build --no-daemon'
            }
    }
}
}
