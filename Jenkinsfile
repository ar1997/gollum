pipeline {
  agent {
    dockerfile {
      filename 'File name ? NO !'
    }

  }
  stages {
    stage('stage1') {
      steps {
        echo 'This is the first stage ?'
        sh '''!#/bin/sh 
echo "Stage one step 2 the shell script"
'''
      }
    }

  }
}