pipeline {
  agent any
  stages {
    stage('Checkout info') { steps { sh 'git log --oneline -3' } }
    stage('Run script')    { steps { sh 'bash hello.sh' } }
  }
}
