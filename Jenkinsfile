pipeline{
   agent any
   triggers {
       cron '* * * * *'
   } 
   stages{
      stage('Saludo'){
          steps{
              echo 'Hola'
              
          }
       
   } 
   
   stage('Version'){
          steps{
              echo 'Version de Maven'
              
          }
       
   } 
   stage('Despedida'){
          steps{
              echo 'Adios'
              
          }
       
   } 
   }
   post{
       always{echo 'PD:salgo siempre'}
       success{echo 'Acabo bien'}
       failure{echo 'Acabo mal'}
       changed{echo 'He cambiado'}
       unstable{echo 'EStoy q no estoy'}
       regression{echo ' A veces fallo otras no'}
       
   }
}
