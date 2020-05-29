node() {
stage 'build'
openshiftBuild(buildConfig: 'testlab2', showBuildLogs: 'true')
stage 'deploy'
openshiftDeploy(deploymentConfig: 'testlab2')
openshiftScale(deploymentConfig: 'testlab2',replicaCount: '1')
}
