pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hello there mystical man'
        sleep 6
        writeFile(file: 'q_file.txt', text: 'hello from Jenkins', encoding: 'utf-8')
        input(message: 'please press some key', id: 'B2B2B', ok: '1', submitter: 'what')
      }
    }
  }
}