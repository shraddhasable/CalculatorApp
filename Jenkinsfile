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

dir('/var/lib/tomcat8/webapps/CalculatorApp_warfile.war') {
    // some block
}
