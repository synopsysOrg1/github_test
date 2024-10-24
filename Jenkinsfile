node {
      checkout scm
      stage("blackduck-security-scan") {
        blackduck_scan product: "blackduck"
      }
}
