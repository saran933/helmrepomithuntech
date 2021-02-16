pipeline{
  
  agent any
  
  stages{
    stage('Checkout code') {
       steps{
       git credentialsId: 'GitHub_Credentials', url: 'https://github.com/saran933/helmrepomithuntech.git'
       }
    }
     stage('untar code') {
       steps{
         sh 'tar -xvf ${workspace}/Test1/*'
       }
    }
  }
}
