@Library('poet-pipeline@master')

def wf = new com.tmobile.sre.jenkins.Workflow()
wf.start(agent_label: "Linux")
//wf.start(agent_label: "Linux", pipeline: "<filename>.yml") // For different pipeline yaml file (default one is pipeline.yml)
//wf.start(agent_label: "Linux", pipeline: "pipeline-template.yml") // For getting a flavor of how templates work with POET

