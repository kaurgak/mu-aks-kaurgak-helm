pipelineHelmContinuousIntegration(
  [
     propertiesFileName:'dev-helm-ci.properties',
     jenkinsJobInitialAgent: 'linux',
     jenkinsJobTimeOutInMinutes: 90,
     jenkinsJobTriggerOnPush: true,
     jenkinsJobTriggerOnMergeRequest: true,
     jenkinsJobRegEx: '^[dev].*',            
     jenkinsJobSecretToken: 'JGP_HELM',
  ]
)