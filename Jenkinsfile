pipeline{
    agent any 
     stages{
          stage("compile"){
              steps{
                 echo "compiling the code"
            }
        }
    
    }
    stage("test"){
        steps{
            script{
           echo "testing the code"
        }
    }
} 
   stage("package"){
       steps{
           script{
            echo "packaging the code"
        }
    }
}
}