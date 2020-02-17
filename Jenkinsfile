node {
   
   stage('SCM Checkout')
   {
git 'https://github.com/javahometech/my-app'
  
 }

   stage('Compile-Package'){
    def mvnHome = tool name: 'maven3', type: 'maven'
      sh "${mvn package}/bin/mvn package"
  }
  }
