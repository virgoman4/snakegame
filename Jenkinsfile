node('master'){
	stage('Cloning Git'){
		checkout scm
	}
	stage('Build-and-Tag'){
		sh 'echo Build-and-Tag'
	}
	stage('Post-to-DockerHub'){
		sh 'echo Post-to-Dockerhub'
	}
	stage('Pull-image-server'){
		sh 'echo Pull-image-server'
	}
}
