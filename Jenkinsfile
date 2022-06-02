// pipeline {
//   agent any
//   stages {
//     stage('Build') {
//       steps {
//         sh 'echo "Hello World"'
//         sh '''
//           echo "Multiline shell steps work too"
//           ls -alh
//         '''
//       }
//     }
//   }
// }

pipeline {
  agent any
  stages {
    
    stage('build') {
      steps {
        echo 'building the application...'
      }  
    }
    
    stage('test') {
      steps {
        echo 'testing the application...'
      }
    }
    
    stage('deploy') {
      steps {
        echo 'deploying the application...'       
      }
    }
  }
}
