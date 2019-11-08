pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                echo "This is build phase"
            }
        }
        stage('Test'){
            steps {
                echo "This is test phase"
            }
        }
        stage('Deploy') {
            steps {
               echo "This is deploy phase"
            }
        }
    }
}
