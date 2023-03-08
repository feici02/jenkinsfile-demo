pipeline {
  agent any

  tools {
    maven "MVN"
  }

  environment {
    VERSION = "1.0.0"
  }

  stages {
    stage("build") {
      steps {
        echo "build the app ${VERSION}..."
        sh "mvn -v"
      }
    }

    stage("test") {
      steps {
        echo "test the app..."
      }
    }

    stage("deploy") {
      steps {
        echo "deploy the app..."
      }
    }
  }
}
