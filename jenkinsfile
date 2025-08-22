node {
    stage('clone') {
    git branch: 'main', url: 'https://github.com/azizbenabbes/jenkinstest.git'
}
    stage('built') {
    sh ' cd jenkinstest/ && javac Main.java'
}
    stage('run') {
    sh 'java Main'
}

}
