<<<<<<< HEAD
node{
    def name = "Senthil Veera"
    echo "Welcome to ${name}"
}
=======
pipeline{
    agent{
        node{
            label 'maven'
        }
    }
    stages{
        stage('Clone code'){
            steps{
                git branch: 'main', url: 'https://github.com/vsknalli/tweet-trend-new.git'
            }
        }
    }
}
>>>>>>> 5452824547b4d64d61fff3bed62a3785ec49942a
