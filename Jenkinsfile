pipleline{
         agent any
            tools
            {
              maven 'mav'
             }
           stages
           { 
               stage('compile stage')
              {
                      steps{
                         sh 'mvn compile'
                           }
                }
                stage('package stage'){
                steps{
                  sh 'mvn package'
                  }
                  }
               }
              }
