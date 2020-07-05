node('master')
{
    stage('ContinuousDownload_Master Branch')
    {
        git 'https://github.com/polisettytharak/maven.git'
    }

    stage('ContinuousBuild_Master Branch')
    {
        sh label: '', script: 'mvn package'
    }
}
