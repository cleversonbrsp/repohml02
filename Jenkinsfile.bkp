pipeline {
    agent any

    stages {
        stage('Checkout Project Repository') {
            steps {
                // Check out the project repository "repohml02.git"
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], userRemoteConfigs: [[url: 'https://github.com/cleversonbrsp/repohml02.git']]])
            }
        }
    }
}



// pipeline {
//     agent any

//     stages {
//         stage('MENSAGEM') {
//             steps {
//                 echo "SEU REPOSITORIO DE ARQUIVOS FOI VALIDADO COM SUCESSO!"
//             }
//         }
//     }
// }
