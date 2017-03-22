node {
   stage 'Checkout'
        checkout scm 

   stage 'Test'
         echo 'testing'
         sh 'uname -a' 

   stage 'Build'
        echo 'building'
        sh 'true'

   stage 'Deploy'
        echo 'Push to Repo'
        sh 'datetime'

   stage 'Cleanup'
        sh 'dh -h' 
}
