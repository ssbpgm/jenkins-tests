pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "building..." 
            }
        }
        stage('Test') { 
            steps {
                echo "testing..."
            }
        }
        stage('Deploy') { 
            steps {
                echo "deploying..."
            }
        }
        stage('finish') {
            steps {
                input("Do you want to say Lola the work is finished?)
                echo("Lola, the job is finished")
            }
    }
}
