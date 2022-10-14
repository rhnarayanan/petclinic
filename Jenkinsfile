pipeline {
	agent any
    stages {
        stage('Build on k8 ') {
            steps {           
                       
                        sh 'pwd'
                        sh 'cp -R helm/* .'
		        sh 'ls -ltr'
                        sh 'pwd'
		        sh 'export KUBECONFIG=/etc/rancher/k3s/k3s.yaml'
                        sh 'helm list'
		        sh 'export KUBECONFIG=/.kube/config'
              			
            }           
        }
    }
}
