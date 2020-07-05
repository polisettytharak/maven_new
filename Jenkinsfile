node('master')
{
    stage('ContinuousDownload_loan Branch')
    {
        git 'https://github.com/polisettytharak/maven.git'
    }
    stage('ContinuousBuild_Loan Branch')
    {
        sh label: '', script: 'mvn package'
    }
}
