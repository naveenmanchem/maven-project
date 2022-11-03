pipeline {
    agent any
     stage('SCM checkout') {
      git 'https://github.com/naveenmanchem/maven-project.git'
    }
    stage('build package'){
     sh 'mvn install'
    }
    }
