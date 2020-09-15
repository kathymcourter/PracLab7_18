pipeline {
    agent any
    stages {
   
       stage("build") {
       
          steps {
              echo 'this is build.  Now it has changed'
              echo 'this is another change and a third change'
          }
       }
       stage("deploy") {
       
          steps {
              echo 'this is deploy'
          }
       }
    }
}
