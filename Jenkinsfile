node {
  stage('Clone') {
    echo "1.Clone Stage"
  }
  stage('Test') {
    echo "2.Test Stage"
  }
  stage('Build') {
    echo "3.Build Stage"
    sleep 120
  }
  stage('Deploy') {
    echo "4. Deploy Stage"
    echo `pwd`
    sh "touch success"
  }
}
