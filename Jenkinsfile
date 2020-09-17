pipeline {

    agent any

    stages {

        stage ('Compile Stage') {

           steps 

              {

                   bat label: '', script: 'mvn compile'

                }

            }

        
        stage ('Testing Stage') {

            steps 

                 {

                    bat label: '', script: 'mvn test'

                }           

        }

        stage ('Package Stage') {

            steps 

                {

                    bat label: '', script: 'mvn package'

                }

            }       

        stage ('Install Stage') {

            steps 

                {

                    bat label: '', script: 'mvn install'

               }
        }
      stage ('Deploy Stage') {

            steps 

                {

                    bat label: '', script: 'mvn tomcat:redeploy'

                }

            }       
        }       
    }
    
    


