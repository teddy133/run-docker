pipeline{
  agent any
  stages{
    stage('install Docker'){
      steps{
        sh "curl -fsSL get.docker.com -o get-docker.sh"
        sh "/var/jenkins_home/workspace/calc.py/get-docker.sh"
        sh "sudo usermod -aG docker nightwing133"
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
