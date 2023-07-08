pipeline
{
  agent any
 
  stages
  {
    stage ('Build')
    {
       steps
       {
         bat 'python new1.py'
         bat 'python -version'
         }
        }
        stage('Run')
        {
           steps
              {
                 bat' new1.py'
              }
             }
            }
         }   
