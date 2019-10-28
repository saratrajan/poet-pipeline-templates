# Quick Readme

This is for testing out the open source POET pipeline library.

## Demo for Templates & Includes
Apart from our basic `pipeline.yml`, we also have created another version of pipeline definition file, which is `pipeline-template.yml` that has the usage of Templates. This pipeline file covers two more steps (in the form of templates from a _remote_ repository which can be utilized from within the native pipeline yml itself) run on [two](https://github.com/tmobile/POET-pipeline-demo/tree/feature/templates/templates) different Step-Containers. More examples and documentation on Templates are available on the [Wiki](https://github.com/tmobile/POET-pipeline-library/wiki/Templates-Includes) for POET.

### Try out yourself
Try out the above by commenting out [#4](https://github.com/tmobile/POET-pipeline-demo/blob/9f0bafdb5884af01a285986eeb040f535d76958e/Jenkinsfile#L4) and un-commenting [#6](https://github.com/tmobile/POET-pipeline-demo/blob/9f0bafdb5884af01a285986eeb040f535d76958e/Jenkinsfile#L6) from the `Jenkinsfile`


## Templating this repo
Please make use of the `Use this template` option to create your own quick repo with all the necessary files to trigger your pipeline with POET.
