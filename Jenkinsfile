pipeline { 

agent any

stages {
      stage ('SCM') {
            steps {
                 echo "git pull my code-1"
                 echo "git pull my code-2"
            }
      }

      stage ('Deploy') {
            steps {
                  echo "deploying my code"
            }

      }

      stage ('Test') { 
            steps {
                  echo "test my final webapp"
            }
      }

}

}