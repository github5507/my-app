node {
  stage ("SCM Checkout"){
    git "https://github.com/github5507/my-app"
  }
  stage("compile-package"){
    //GET MAVEN HOME PATH
    def mvnHOME = tool name: 'maven-3', type: 'maven'
    sh "${mvnHOME}/bin/mvn package"
  }
}
