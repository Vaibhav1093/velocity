
pipeline {
         agent {
                 label {
                         label 'built-in'
                         customworkspace '/mnt/myproject'
                    
                      }
              }
              
                stages {

                       stage ('stage-1') {
                                    steps {
                                          sh "mkdir test"
                              }
                          }

                    stages {

                       stage ('stage-2') {
                                    steps {
                                          sh "mkdir folder1"
                              }
                          }
       }
}
