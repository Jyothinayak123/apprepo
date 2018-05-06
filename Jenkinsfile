pipeline {
         agent any
            tools
            {
              maven 'Mav'
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
