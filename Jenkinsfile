pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''echo "================"
pwd
echo "================"
ls -l
echo "================"
'''
        sh 'mvn clean package -Dmaven.test.skip=true'
        sh '''echo "================"
pwd
echo "================"
ls -l
echo "================"
'''
      }
    }

  }
}