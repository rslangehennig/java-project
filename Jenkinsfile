pipeline {
  agent {
     label 'rslangehennig2'
  }

  stages {
     stage('build') {
       steps {
          sh 'ant -f build.xml -v'
       }
     }
  }

  post {
     always {
        archiveArtifacts 'dist/*.jar'
     }
  }

}
