pipeline {
    agent {label 'swarm'}
    stages {
        stage('GradleBuildTest') {
            steps {
                sh './gradlew build --no-daemon'
            }
        }
    }
}.
