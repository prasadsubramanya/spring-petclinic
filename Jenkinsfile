node()
{
    stage('Checkout'){
        checkout scm
    }

    stage("Welcome"){
        def userInput = input(id: 'userInput', message: 'Enter name',parameters: [string(defaultValue: 'None',name: 'Config')])
    }


}