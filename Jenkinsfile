pipeline {
    agent any
    stages {
      stage('Upload to AWS') {
        stage('Lint HTML') {
        steps {
          sh 'tidy -q -e *.html'
        }
        }
      }
    }
}
