node {
   
   stage('Code Checkout') { // for display purposes
      // Get some code from a GitHub repository
    git credentialsId: 'Github-ID', url: 'https://github.com/pratyush2/CounterApp.git'}
      }
      
   stage('Build') {
     withMaven(jdk: 'jdk 1.8', maven: 'maven 3.5.3') {
    // some block
       sh 'mvn clean install'
     }
   }
