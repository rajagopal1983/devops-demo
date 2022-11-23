node {
   
   stage("Checkout")
   {
       git credentialsId: 'cafb5d74-b911-4bbd-afdf-b19f16a44c1d', url: 'https://github.com/rajagopal1983/devops-demo.git'
   }
   
   stage("Build")
   {
       echo "my build stage"
       bat 'mvn --version'
   }
   
   stage("Test")
   {
       echo "my test stage"
   }
   
   stage("Deployment")
   {
       echo "my deployment stage"
   }
}
