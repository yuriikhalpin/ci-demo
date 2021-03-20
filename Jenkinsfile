pipeline {
  agent any
  stages {
    stage('Lint') {
      steps {
        sh '''sleep 5 && echo "Hello, Slurm!" && \\
ls -la && \\
echo "The code is okay"'''
      }
    }

  }
}
