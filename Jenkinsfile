pipeline {

 agent any

 stages {
  stage('GIT') {
  
   steps{
    git branch: 'main', credentialsId: 'c4d00eab-827f-4380-8985-50c2267b921f', url: 'https://github.com/gamidi95/gamidi95.git'
   }
  
  }
  /*stage('Maven'){ 
   steps{ 
    build 'PipeLprj1'
   }
  } *\
  
 }
 
 /* stages {

    stage('build in master') {

      steps {

        echo 'Hello World'

      }

    }

    stage('test in master') {

  when {

  branch comparator: 'EQUALS', pattern: 'test'

  }

      steps {

        echo 'Hello World'

      }

 }

    stage('deploy in master') {

      steps {

        echo 'Hello World'

      }

    }

 stage('build') {

 when {

  branch comparator: 'EQUALS', pattern: 'test'

  }

      steps {

        echo 'Hello World'

      }

    }

    stage('test') {

  when {

  branch comparator: 'EQUALS', pattern: 'test'

  }

      steps {

        echo 'Hello World'

      }

 }

    stage('deploy') {

 when {

  branch comparator: 'EQUALS', pattern: 'test'

  }

      steps {

        echo 'Hello World'

      }

    }

 }

 post {

 always {

  cleanWs()
 }

 }
*/
}














