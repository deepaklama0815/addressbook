node('maven'){
    def mvnhome = tool name: 'maven360', type: 'maven'

stage('checkout'){
    git credentialsId: 'github-passwd', url: 'https://github.com/deepaklama0815/addressbook.git'
}
stage('test'){
    sh "${mvnhome}/bin/mvn clean compile"
    junit 'target/surefire-reports/*.xml'

}
stage('package'){
    sh "${mvnhome}/bin/mvn package"
}
}
