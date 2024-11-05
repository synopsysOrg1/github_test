pipeline {
    agent any

    stages {
        
       stage("Black-Duck-Security-Scan") {
           steps {
               script {
                    security_scan product: 'blackducksca',
                    bridgecli_download_url: 'https://artifactory.internal.synopsys.com/artifactory/clops-local/clops.sig.synopsys.com/bridge/binaries/bridge-cli-bundle/latest/bridge-cli-bundle-macosx.zip'
               }
           }
        }
    }
}
