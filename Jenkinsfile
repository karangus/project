node {
    stage('SCM') {
        git 'https://github.com/karangus/project.git'
    }
    
    stage('Build') {
     
             sh label: '', script: 'mvn package'
        }
    
    
    
    stage('Results'){
        archive 'target/project143.war'
    }
}
