pipeline {
  agent {
    node {
      label 'centof7'
    }

  }
  stages {
    stage('CheckOut from Githyb') {
      steps {
        git(url: 'https://github.com/aviadhager/pipelines-dotnet-core.git', branch: 'master', credentialsId: 'github')
      }
    }

  }
}