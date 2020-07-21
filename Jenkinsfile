node{
  stage('SCM Checkout'){
    git 'https://github.com/GaddeLaxmi/SimpleCalculaterApplication'
    }
    stage('Compile and Package'){
      //get mvn home pack
      def mvnhome = tool name: 'Maven', type: 'maven'
      sh "${mvnhome}/bin/mvn package"
    }
  }
