pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
			build 'MavenNew1'
				}
        }
        stage('Test'){
            steps {
			build 'MavenNew2'
            }
        }
    }
}



