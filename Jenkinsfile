pipeline {
    agent any

    stages {
        stage('Git Checkout') {
    steps {
        git branch: 'master',
    url: 'https://github.com/kliakos/sparkjava-war-example.git'
    }
}
       stage('Build') {
    steps {
        sh 'mvn -U clean package'
    }
}
    }
}
