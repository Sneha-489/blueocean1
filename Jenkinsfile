pipeline {
  agent any
  stages {
    stage('Plan') {
      parallel {
        stage('Plan') {
          steps {
            echo 'Plan stage'
          }
        }

        stage('Code') {
          steps {
            echo 'Code Stage'
          }
        }

        stage('Build') {
          steps {
            echo 'Build Stage'
          }
        }

      }
    }

    stage('Operate') {
      steps {
        echo 'Operate Stage'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy Stage'
      }
    }

  }
}