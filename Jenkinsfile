pipeline {
	agent any
	stages {
		stage('linux_64bit') {
			steps {
				sh './test.sh | diff - ./testdata.txt'
			}
		}
	}
}
