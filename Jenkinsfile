
node {

  stage('poll repo') {
    git credentialsId: '6f534bba-9b93-49fa-b49c-0f0b054dce12', url: 'https://github.com/fscoding/packer-wordpress.git'
  }

  stage('packer validate') {
    sh 'packer validate packer-wordpres.json'
  }

}
