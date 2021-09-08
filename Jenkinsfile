node{
    def buildNumber = BUILD_NUMBER
   stage("Git CheckOut"){
        git url: 'https://github.com/vigneshwaran3/java-web-app-docker.git',branch: 'master'
   } 
      stage(" Maven Clean Package"){
      def mavenHome =  tool name: "Maven", type: "maven"
      def mavenCMD = "${mavenHome}/bin/mvn"
      sh "${mavenCMD} clean package"
       } 
    
   
