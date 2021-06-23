pipeline {
    agent any

    stages {
        stage('Build'){
            steps {
            // git 'https://github.com/spring-petclinic/spring-petclinic-angularjs.git'
            sh 'ls -l && cd pet-clinic-app && chmod +x mvnw &&  ./mvnw clean install && cd spring-petclinic-server \
            && ../mvnw spring-boot:run '

            }
        }
        // stage('Test'){
        //     steps{

        //     }
        //     post {
        //         always {
        //             junit '**/target/TEST-*.xml'
        //         }
        //     }
        }
    }
    
