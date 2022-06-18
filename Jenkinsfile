properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git "https://github.com/yargov68/MySoftware.git"
    }
    stage("show files"){
        bat 'dir'
    }
}
