pipeline {
   agent any
   stages {
     stage('build') {
       steps{
         echo "these are release artifacts"
         sh "cat pom.xml"
         }
        }
       }
   post {
      always {
         archive "/home/user/zipp/*.jar"
      }
   } 
 } 
