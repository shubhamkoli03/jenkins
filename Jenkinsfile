pipeline {
    agent any
    
    stages {
        stage(push) {
            steps {
                echo "push the code"
            }
        }
        stage(build) {
            steps {
                echo "build the code"
            }
        }
        stage(test) {
            steps {
                echo "test the code"
            }
        }
        stage(prod) {
            steps {
                echo "deploy the code in production"
            }
        }
    }
}
