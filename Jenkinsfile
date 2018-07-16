pipeline{
  agent any
  stages{
    stage('install Docker'){
      steps{
        sh "sudo su"
        sh "cd /var/jenkins_home/run-docker"
        sh "./get-docker.sh"
        sh "sudo docker version"
}
}
    stage('Docker Build'){
      steps{
        sh "docker run --name jenkins hello-world"
}
}
}
}
