pipeline {
  agent 'rslangehennig2'

  stages {
     stage('build') {
       steps {
          sh 'ant -f build.xml -v'
       }
     }
  }
}
