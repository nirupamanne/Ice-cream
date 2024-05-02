pipeline {
    agent any

    stages {
        stage('Hello Niru') {
            steps {
                bat 'javac HelloNiru.java'
                bat 'java HelloNiru'
            }
        }
        stage('Hello Vinni') {
            steps {
                bat 'javac HelloVinni.java'
                bat 'java HelloVinni'
            }
        }
        stage('Hello Lokhi') {
            steps {
                bat 'javac HelloLokhi.java'
                bat 'java HelloLokhi'
            }
        }
      stage('Hello Madhu') {
            steps {
                bat 'javac HelloMadhu.java'
                bat 'java HelloMadhu'
            }
      }
    }
    post {
        always {
            script {
                // Clean up
                deleteDir()
            }
        }
    }
}
