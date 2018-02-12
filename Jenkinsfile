node('maven') {
stage 'build'
       openshiftBuild(buildConfig: 'sample-build', showBuildLogs: 'true')
       stage 'deploy'
       openshiftDeploy(deploymentConfig: 'app')
}