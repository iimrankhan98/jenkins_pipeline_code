pipeline {

     agent any

     stages {

          stage ('Check Out SCM') {
               steps {
                    echo "git pull mycode"
               }
               
          }
          stage ('Build') {
               steps {
                    echo "Build by maven"
               }
          }
          stage ('Deploy to DEV?') {
               steps {
                    echo "deploy to dev env"
               }
          }
          stage ('Deploy to QA?') {
               steps {
                    echo "deploy to qa env"
               }
          }
          stage ('Cleanup Stage') {
               steps {
                    echo "Cleanup Step"
                    cleanWs ()
               }
          }


     }
}