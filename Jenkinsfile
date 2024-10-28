pipeline {
    agent any

    stages {
        
       stage("Black-Duck-Security-Scan") {
           steps {
               script {
                    security_scan product: 'blackducksca', blackducksca_prComment_enabled: true
               }
           }
        }
    }
}
