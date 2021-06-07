node {
  stage ("SCM Checkout"){
    git "https://github.com/github5507/my-app"
  }
  Stage("compile-package"){
    sh "mvn package"
  }
}
