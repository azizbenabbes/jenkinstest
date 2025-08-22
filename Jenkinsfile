node {
    stage('clone') {
    git branch: 'main', url: 'https://github.com/azizbenabbes/jenkinstest.git'
}
    stage('built') {
    sh '  javac Main.java'
}
    stage('run') {
    sh 'java Main'
}

}

