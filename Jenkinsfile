pipeline {
agent any
stages {
stage('Build') {
steps {
sh 'g++ main/hello.cpp'
build 'PES1UG21CS814 -1'
}
}
stage('Test') {
steps {
sh './a' 
}
}
stage('Deploy') {
steps {
echo 'Application is deployed'
}
}
}
post {
failure{
echo 'Pipeline failed'
}
}
}
