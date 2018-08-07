def workspace;
node('Slave-1') {
    stage('SCM CHECKOUT') {
        
        git 'https://github.com/ramachandran19902011/my-app.git'
        workspace=pwd()
    }
    stage('STATIC CODE ANALISIS'){
        echo 'Static Code Analysis'
    }
    stage('BUILD'){
        echo 'Build the code'
    }
    stage('UNIT TESTIG'){
        echo 'Unit test phase'
    }
    stage('DELIVERY'){
        echo 'Delivery'
    }
}
                 

  
