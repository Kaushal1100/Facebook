
pipeline{
  agent any
parameters {
               string(name: 'Version',
               defaultValue: 'facebook-2.0',
               description: 'Facebook Project')
        }
 stages{
       stage('Checkout'){
                          steps{
                          checkout([$class: 'GitSCM', branches: [[name: '*/facebook-2.0']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Kaushal1100/facebook.git']]])
                          }
       }
 }

}
