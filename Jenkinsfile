node {
      checkout scm
      stage("blackduck-security-scan") {
        security_scan product: "blackduck"
      }
}
