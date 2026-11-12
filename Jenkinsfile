pipeline {
    agent any

    stages {
        stage('Git Checkout') {
    steps {
        deleteDir()
        git branch: 'master',
            url: 'https://github.com/narayan9403/sparkjava-war-example1.git'
    }
}
       stage('Build') {
    steps {
        sh 'mvn -U clean package'
    }
}
    }
}
