node('master') 
{
    stage('ContinuousDownload_master') 
	{
    git 'https://github.com/venkadali/maven.git'
	}
    stage('Continuousbuild_master') 
	{
    sh label: '', script: 'mvn package'
	}
}
