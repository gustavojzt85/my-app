node{
	stage('SCM Checkout'){
		git 'https://github.com/gustavojzt85/my-app'
	}
	stage('Compile package'){
		sh 'mvn package'
	}
}
