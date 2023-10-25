pipeline{
  agent any
  stages {
    stage('Deploy')
    {
      steps {
        script {
          data = load 'task7.groovy'
          data.func('PROD')
        }
      }
    }
  }
}
