node {
    stage('SCM Checkout'){
         git 'https://github.com/vsknalli/tweet-trend-new.git'
         
    }
    stage('Compile and package'){
        sh 'mvn package'
    }
}