node{
    stage ('checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '93d22f30-1ac1-4d38-bb3e-d89b0676ad69', url: 'https://github.com/keerthuchow/First.git']]])
    }
}