pipeline { 
agent any
stages { 
stage('Checkout'){
steps{
echo'Checkingoutsourcecode...'
}
}

stage('Build')
{ steps 
{
echo'Buildingtheapplication...'
}
}

stage('Test'){ steps {
echo 'Testing the application...' 
echo'Alltestspassedsuccessfully!'
}
}

stage('Deploy'){ steps {
echo'Deploying application...'
echo'Application deployed successfully!'
}
}
}
}
