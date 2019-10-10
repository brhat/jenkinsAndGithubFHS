pipeline {
    agent none
	stages {
		stage('linux_64bit') {
			steps {
				catchError { sh './test.sh | diff -q - testdata.txt' }
			}
		}
	}
}
