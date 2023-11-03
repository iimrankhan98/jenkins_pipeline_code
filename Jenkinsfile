pipeline { 

agent any

Stages {
      stage ('SCM') {
            steps {
                 echo "git pull my code-1"
                 echo "git pull my code-2"
            }
      }

      Stage ('Deploy') {
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