node {
     stage('SCM Checkout'){
      git 'https://github.com/Ramfunc/samplebootmvn'     
     }
     stage('Compile-Package'){
       bat 'mvn clean -Dmaven.clean.failOnError=false package'     
     }


}
