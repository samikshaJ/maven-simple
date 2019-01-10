node {
     stage('SCM Checkout'){
          git 'https://github.com/samikshaJ/maven-simple'
     }
     stage('Compile-Package'){
          def mvn = tool name: 'Maven', type: 'maven'
          sh "${mvn}/bin/mvn package"
     }
}
