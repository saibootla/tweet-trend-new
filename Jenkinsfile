pipeline {
    agent {
        label 'maven'
    } 
    
    stages {
        stage ('checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/saibootla/tweet-trend-new.git'
            }
        }
    }
}