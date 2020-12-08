node {
    def mvnHome = tool 'MAVEN'

    stage('Checkout') {
        checkout scm
    }

    stage('Build') {
        sh "${mvnHome}/bin/mvn -B package"
    }
}
