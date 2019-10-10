pipeline {
	agent any
	stages {
		stage('linux_64bit') {
			steps {
				sh 'pwd'
				sh './test.sh | diff - testdata.txt'
			}
		}
	}
}
