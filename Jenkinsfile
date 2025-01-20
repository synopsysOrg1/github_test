pipeline {
    agent any
    stages {
        stage('BlackDuckSecruityScan') {
            steps {
                script {
                    def status = security_scan product: 'blackducksca'
                    "JENKINS_HOME: ${env.JENKINS_HOME}"    
                }
            }
        }
    }
}
