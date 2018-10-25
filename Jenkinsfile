pipeline { 
    agent any 
    stages {
        stage('Build') { 
            steps { 
                echo 'Dev' 
            }
        }
        stage('Test'){
            steps {
            echo 'QA'
		  }
        }
        stage('Deploy') {
            steps {
               echo 'env'
            }
        }
    }
}
