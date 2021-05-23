pipeline{
    agent any
    stages{
        stage("test"){
            steps{
            echo "hello handsome"
            }
        }
        
        stage("trigger"){
            steps{
            SCM('* * * * *')
            }
        }
        
    
        
        stage("build"){
            steps{
            echo "hii Awesome"
    }
}
    }
    
}
