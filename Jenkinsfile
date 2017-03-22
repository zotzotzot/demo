node {
   stage 'Checkout'
        checkout scm 

   stage 'Test'
         echo 'testing'
         sh 'uname -a' 

   stage 'Build'
        echo 'building'
        sh 'exit 1'

   stage 'Deploy'
        echo 'Push to Repo'
        sh 'date'

   stage 'Cleanup'
        sh 'df -h' 
}
