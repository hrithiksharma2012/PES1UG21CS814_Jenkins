pipeline {
agent any
stages {
stage('Build') {
steps {
sh 'g++ main/newfile.cpp'
build 'PES1UG21CS813-1'
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
