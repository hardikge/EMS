// Powered by Infostretch 

timestamps {

node () {

	stage ('DM - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'git', url: 'https://github.com/hardikge/EMS.git']]]) 
	}
}
}