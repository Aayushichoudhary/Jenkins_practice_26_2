pipeline 
     {
      agent any
      stages
      {
       stage('git')
       {
        steps
            {
              git "https://github.com/Aayushichoudhary/Jenkins_practice_26_2.git"
              }
}
        stage('run')
        {
         steps
            {
             sh "java demo.java"
             sh "python3 main.py"
             }
        }
       
      }//stages
      }//pipeline
