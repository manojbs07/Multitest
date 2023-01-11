pipeline {
    agent any

    stages {
        
        stage('SCM Checkout') {
            steps {
                echo 'This is SCM checkout stage'
                sh 'sleep 5' 
           
            }
        }
        stage('Build') {
            steps {
                echo 'This is Build stage'
                sh 'sleep 5' 
            }
        }
        stage('Push') {
            steps {
                echo 'This is Push stage'
                sh 'sleep 5' 
            }
        }
        stage('Deploy') {
            steps {
                echo 'This is deployment stage'
                sh 'sleep 5' 
            }
        }
         stage('Test') {
            steps {
                echo 'This is Test stage'
                sh 'sleep 5' 
            }
          } 
       }
    }
