pipeline{
    agent {
    docker { image 'node:16-alpine' }
  }
   stages{
       stage('test1'){
           steps{
               sh 'node --version'
           }
       }
        stage('test2'){
           steps{
               sh 'node --version'
           }
       }
   }
}
