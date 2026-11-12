pipeline {
    agent any

    stages {
        stage('Git Checkout') {
    steps {
        git branch: 'master',
            url: 'https://github.com/kliakos/sparkjava-war-example1.git'
    }
}
       stage('Build') {
    steps {
        sh 'mvn -U clean package'
    }
}
    }
}
