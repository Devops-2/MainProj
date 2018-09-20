node {
   
   stage ("get Code from SCM") { 
       
     checkout([$class: 'GitSCM', branches: [[name: '*/develop']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'sspgithubcreds', url: 'https://github.com/Devops-2/MainProj.git']]])
       
   }
   
   stage("echo statement") {
       sh 'ls -ltr '
   }
   
}
