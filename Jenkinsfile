node() {
stage 'build'
openshiftBuild(buildConfig: 'myphp1', showBuildLogs: 'true')
stage 'deploy'
openshiftDeploy(deploymentConfig: 'myphp1')
openshiftScale(deploymentConfig: 'myphp1',replicaCount: '2')
}
