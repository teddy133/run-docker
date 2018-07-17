pipeline{
  agent any
  stages{
    stage('install Docker'){
      steps{
        sh "sudo su"
        sh "cd /var/jenkins_home/run-docker"
}
}
    stage('Docker Build'){
      steps{
        sh "sudo docker build -t nightwing133/run-docker ."
}
}
    stage('Docker Push'){
      steps{
        sh "sudo docker push nightwing133/run-docker"
}
}
}
}
