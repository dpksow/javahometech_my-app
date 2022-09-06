node{
   stage('SCM Checkout'){
     git 'https://github.com/SrMani90/javahometech_my-app.git'
   }
   stage('Compile-Package'){
      // Get maven home path
      def mvnHome =  tool name: 'maven', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
   }
   
}
