node()
{
    stage('Checkout'){
        checkout scm
    }

    stage("Welcome"){
        env.userInput = input(id: 'userInput', message: 'Enter name',parameters: [string(defaultValue: 'None',name: 'Name')])
        echo "${env.userInput}"
    }


}