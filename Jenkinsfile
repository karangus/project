node {
    stage('SCM') {
        git 'https://github.com/karangus/project.git'
    }
    
    stage('Build & Package') {
     
            sh 'sh label: '', script: 'mvn package'
        }
    
    
    
    stage('Results'){
        archive 'target/project.war'
    }
}