pipeline {
agent any 
stages {
stage ('Build') {
steps {
echo 'Building'
sh "touch test.txt"
}
}
stage ('Test') {
steps {
echo "Test"
sh "ls -lahtr"
}
}
}
}

