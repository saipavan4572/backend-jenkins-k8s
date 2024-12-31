@Library('jenkins-shared-library') _

// create variable of map type and set the values

def configMap = [
    type: "nodejsEKS",
    component: "backend",
    project: "expense"
]

pipelineDecision.decidePipeline(configMap)

/* if( ! env.BRANCH_NAME.equalsIgnoreCase('main')){
    // calling a method in jenkins-shared-library app/module
    pipelineDecision.decidePipeline(configMap)
}
else{
    echo "Proceed with CR or NON-PROD pipeline"
} */
