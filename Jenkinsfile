node {
  stage ("SCM Checkout"){
    git "https://github.com/github5507/my-app"
  }
  stage("compile-package"){
    sh "mvn package"
  }
}
