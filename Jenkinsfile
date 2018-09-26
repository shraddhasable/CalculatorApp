#!groovy

stage 'build'
node{
    checkout scm
    sh 'mvn package'
}

stage 'test'
node{
    checkout scm
    sh 'mvn test'
}
