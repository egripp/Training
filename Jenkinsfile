
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Step 1'
		
		sh 'sleep 5'

		echo 'Step 2'
		
		sh 'sleep 5'
		
		echo 'Step 3'
		    
		sh 'sleep 5'
		    
		sh 'cat README.md'
		    
		    
		sh 'sleep 5'
		    
		sh 'pip install -r requirements.txt'
		    
		sh 'docker build -t friendlyhello .'
		
		sh 'docker run -p 4000:80 friendlyhello'
		    
		sh 'sleep 5'
		    
		echo 'Fim do primeiro pipeline'
            }
	    
        }
    }
}

