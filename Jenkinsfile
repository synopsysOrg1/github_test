node {
      checkout scm
      stage("black-security-scan") {
        black_scan product: "blackduck"
      }
}
