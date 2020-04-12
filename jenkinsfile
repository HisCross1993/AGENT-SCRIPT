pipeline {
   agent any

   stages {
      stage('build') {
         steps {
            echo 'build steps'
            sleep 4
         }
      }
       stage('test') {
         steps {
            echo 'test step'
            sleep 10
         }
      }
       stage('deploy') {
         steps {
            echo 'deployment '
            sleep 10 
         }
      }
   }
}
