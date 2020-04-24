node {
    stage('SCM') {
		echo 'Gathering code from version control'
		git branch: '${branch}', url: 'https://github.com/trussbtech/btech_android_app.git'
    }
    stage('Build') {
		echo 'Building Master branch'
		sh 'dotnet --version'
		sh 'dotnet build '
		echo 'The build stage passed...'
	}	
	 
	stage('Tests') {
		echo 'The testing stage passed...'
	}
	
    stage('Test') {
		echo 'Testing At master branch'
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}
