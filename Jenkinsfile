node {
   stage('Preparation') {
      git 'https://github.com/harrypod/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}
