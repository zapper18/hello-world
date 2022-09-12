pipeline
{
	agent any
		stages {
			stage ('checkout'){
				steps {
					checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/zapper18/hello-world.git']]])
					}
						}
			}
}




