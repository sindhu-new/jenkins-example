pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
               
                    sh 'mvn clean compile'
                }
            }
        

        stage ('Testing Stage') {

            steps {
                
                    sh 'mvn test'
                }
            }
        


        stage ('install Stage') {
            steps {
                
                    sh 'mvn install'
                }
            }
        
    }

