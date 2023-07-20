pipeline{
   agent any
   environment{
      PATH = "$PATH:/opt/apache-maven-3.6.3/bin"
   }
   stages{
      stage('Get Code'){
         steps{
            git 'https://github.com/AbhishekJha6267/New-job.git'
         }
      }
      stage('Build Code'){
         steps{
            sh 'mvn clean package'
         }
      }
   }
}