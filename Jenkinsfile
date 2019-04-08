node('maven'){
    def mvnhome = tool name: 'maven360', type: 'maven'
}
stage('checkout'){
    git credentialsId: 'github-passwd', url: 'https://github.com/deepaklama0815/addressbook.git'
}
