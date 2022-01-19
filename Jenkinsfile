pipeline {
  environment {
        imageName = "subs-swarajya"
        registry = "registry.digitalocean.com"
        registrySlug = "cms-swarajya"
        dockerImage = ''
        latest = "latest"
    }
  agent any
  stages {
   stage('Building Image') {
      steps{
        script {
           sh './jenkins/part.sh'
        }
      }
    }
  }
}