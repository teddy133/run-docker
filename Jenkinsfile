pipeline{
  agent any
  stages{
    stage('install Docker'){
      steps{
        sh "sudo su"
        sh "cd /var/jenkins_home/run-docker"
        sh "./get-docker.sh"
}
}
    stage('Docker Build'){
      steps{
        sh "sudo docker run --name jenkins hello-world"
}
}
}
}
