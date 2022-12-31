node{
    
    stage('clone java project') {
    git branch: 'main', url: 'https://github.com/knbtechnosys/DevOps_7PM_Batch.git'
}

stage('Build Maven target') {
   sh 'mvn install'
}
    
    
    
}
