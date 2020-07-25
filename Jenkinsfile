pipeline {
    agent any
    stages {
        stage('Sonar') {
            steps {
                mvn sonar:sonar \
                  -Dsonar.projectKey=test-project \
                  -Dsonar.host.url=https://sonarqube-sonarqube.apps.okd4.okd.gomel.iba.by \
                  -Dsonar.login=dec42f61a73189c8301d81dc5491c140a0d601a8
            }
        }
    }
}
