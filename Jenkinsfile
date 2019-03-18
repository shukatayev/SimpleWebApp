node {
   stage('Preparation') {
      git 'https://github.com/shukatayev/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}