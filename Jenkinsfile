pipeline{
  agent any
  stages{
    stage('install Docker'){
      steps{
        sh "sudo su"
        sh "whoami"
        sh "cd /var/jenkins_home/run-docker"
}
}
    stage('Docker Build'){
      steps{
        sh "sudo docker build -t nightwing133/run-docker ."
}
}
}
}
