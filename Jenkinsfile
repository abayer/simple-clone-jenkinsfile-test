stage('Check for file') {
  node {
    checkout scm
    contents = readFile("README.md")
    echo("README.md exists with content '${contents}'")
  }
}
