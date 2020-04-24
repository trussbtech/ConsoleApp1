node {
    stage('SCM') {
		echo 'Gathering code from version control'
		git branch: '${branch}', url: 'https://github.com/trussbtech/ConsoleApp1.git'
    }
    stage('Build') {
		echo 'Building Master branch'
		sh 'dotnet --version'
		sh 'dotnet build ConsoleApp1'
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
