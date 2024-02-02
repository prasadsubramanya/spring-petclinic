parameters {
        string(name: 'Name', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
}
node()
{
    stage('Checkout'){
        checkout scm
    }

    stage("Welcome"){
        env.userInput = input(id: 'userInput', message: 'Enter name',parameters: [string(defaultValue: 'None',name: 'Name')])
        echo "${env.userInput}"
        echo "${params.Name}"


    }


}