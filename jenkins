pipeline {
    agent any

    stages {
        stage('Git-Hub') {
            steps {
                git branch: 'main', url: 'https://github.com/nitinreddy1324/spring-petclinic.git'
            }
        }
        stage('Build-grneration') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
