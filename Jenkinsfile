pipeline {
  agent any
  triggers {
    upstream(upstreamProjects: "junky/master,jinky/master")
  }
  stages {
    stage('Chunky') {
      steps {
        sh '''
            echo "Bonjour"
            sleep 30
        '''
      }
    }
  }
}