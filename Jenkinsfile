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
        sh "sudo docker run --name first-try hello-world"
}
}
}
}
