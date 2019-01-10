node {
     stage('SCM Checkout'){
          git 'https://github.com/samikshaJ/maven-simple'
     }
     stage('Compile-Package'){
          def mvnHOME = tool name: 'Maven', type: 'maven'
          sh "${mvnHome}/bin/mvn package"
     }
}
