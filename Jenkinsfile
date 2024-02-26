clone{
  stage('SCM Checkout'){
    git 'https://github.com/papadiouf13/vente_voiture'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
