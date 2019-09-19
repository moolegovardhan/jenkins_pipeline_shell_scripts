node {
   
   	stage 'Stage 1'
   		echo 'Hello there, shell scripts'
   	stage 'Checkout'
   		git url: 'https://github.com/TTFHW/jenkins_pipeline_shell_scripts.git'
   	stage 'Build'
   		bat 'myBuild.sh'
   	stage 'Deploy'
   		bat './myDeployment.sh'
  
}
