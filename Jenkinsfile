pipeline{
  agent any
  stages{
    stage('install Docker'){
      steps{
        sh "sudo su root"
        sh "whoami"
        sh "cd /var/jenkins_home/run-docker"
}
}
    stage('Docker Build'){
      steps{
        sh "sudo docker container run --name john hello-world"
}
}
}
}
