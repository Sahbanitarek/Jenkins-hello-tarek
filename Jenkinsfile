node {
    stage('clone') {
   git branch: 'main', url: 'https://github.com/Sahbanitarek/Jenkins-hello-tarek.git'
                   }
    
    stage('build') {
    sh 'javac Main.java'
                   }
    stage('run') {
    sh 'java Main'
                   }
    
}
