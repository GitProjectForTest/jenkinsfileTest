pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                echo "Inside Build Stage"
            }
        }
        stage('Test'){
            steps {
                echo "Inside Test Stage"
            }
        }
        stage('Deploy') {
            steps {
                echo "Inside Deploy Stage"
            }
        }
    }
}
