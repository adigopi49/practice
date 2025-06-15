pipeline {
  agent {label "w1"}
  tools {
    jdk "java17"
    maven "maven3"
  }
  stages {
    stage("git_checkout"){
      steps {
        git branch: 'main', url: 'https://github.com/adigopi49/practice.git'
      }
    }
  }
}
