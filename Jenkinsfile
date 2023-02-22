pipeline {
    agent any

    stages {

        stage('eb create') {
            steps {
                sh 'eb init'
		sh 'eb create jenkins-lucatic'
            }
        }
    }
}
