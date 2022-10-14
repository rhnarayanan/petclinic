pipeline {
	agent any
    stages {
        stage('Build on k8 ') {
            steps {           
                       
                        sh 'helm install mysqldb mysql-1.6.9.tgz'
              			
            }           
        }
    }
}
