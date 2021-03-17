pipeline {
  agent any
  stages {
    stage('step01') {
      steps {
        echo 'Hello world!'
      }
    }

    stage('step02') {
      steps {
        emailext(subject: 'Hello!', body: 'You smell and I sent this with a pipeline job. Be proud of me and please reply', from: 'lindsay.benkel@gmail.com', replyTo: 'lindsay.benkel@gmail.com', to: 'awarnock057@gmail.com')
      }
    }

  }
}