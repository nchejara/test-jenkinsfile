pipeline {

      agent any

      options {
          buildDiscarder(logRotator(numToKeepStr: '1')) 
          timeout(time: 5, unit: "MINUTES")
      }
      
      stages {
      
          stage("Building") {
      
              steps {
                  echo "Building ..."
              }
          }

          stage("Testing") {

              steps {
                  echo "Testing ..."
              }
          }

          stage("Deploying") {
              steps {

                  echo "deploying ..."
              }
          }

      }
  }
