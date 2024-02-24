properties([pipelineTriggers([pollSCM('*/30 * * * *')])])
node {
    stage("clone") {
        git branch: 'main', url: 'https://github.com/ogkatzu/MySwoftware_1'
    }
    stage("show files"){
        sh "ls -l"
    }
}