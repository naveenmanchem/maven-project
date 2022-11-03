pipeline {
    agent any
     stage('SCM checkout') {
         agent{
             label 'node-01'
         }
         steps{
      git 'https://github.com/naveenmanchem/maven-project.git'
    }
     }
    stage('build package'){
        agent{
             label 'node-01'
         }
        steps{
     sh 'mvn install'
    }
    }
    }
