node('maven'){
    def mvnhome = tool name: 'maven360', type: 'maven'

stage('checkout'){
    git credentialsId: 'github-passwd', url: 'https://github.com/deepaklama0815/addressbook.git'
}
//stage('test'){
  //  sh "${mvnhome}/bin/mvn clean compile"
   // sh "${mvnhome}/bin/mvn clean test surefire-report:report-only"
    //junit allowEmptyResults: true, testResults: 'target/surefire-reports/*.xml'
//}
//stage('package'){
  //  sh "${mvnhome}/bin/mvn package -Dskiptest"
//}
//stage('archiving'){
   // archiveArtifacts allowEmptyArchive: true, artifacts: 'target/surefire-reports/*'
//}
//stage('publishing html report'){
  //  publishHTML([allowMissing: false, alwaysLinkToLastBuild: false, keepAll: false, reportDir: 'target/site/', reportFiles: 'surefire-report.html', reportName: 'HTML Report', reportTitles: ''])
//}
//stage('deployment'){
  //  sshagent(['new-machine']) {
    //sh "scp -o StrictHostKeyChecking=no /home/ec2-user/workspace/addressbook-pipeline/addressbook_main/target/addressbook.war ec2-user@54.236.4.88:/home/ec2-user/"
//}
//}
}
