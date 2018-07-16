#!groovy

node('win') {
    stage('CheckoutAndBuild') {
        def response = httpRequest 'http://localhost/Home/DropDb.ps1'
        println("Status: "+response.status)
        println("Content: "+response.content)
    }
}
