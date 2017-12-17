pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hello there mystical man'
        sleep 6
        writeFile(file: 'q_file.txt', text: 'hello from Jenkins', encoding: 'utf-8')
        pwd(tmp: true)
        echo 'finished'
      }
    }
    stage('test') {
      steps {
        echo 'this was edited directly in the Jenkinsfile on GitHub. Hurra!'
        sleep 6
        echo 'this was edited directly in the Jenkinsfile on GitHub. Hurra!'
      }
    }
  }
}
