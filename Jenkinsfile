#!/usr/bin/env groovy
//Leave the above line alone.  It identifies this as a groovy script.
@Library('vs-common-build') _

def lvVersions = ['2017', '2018', '2019']

ni.vsbuild.PipelineExecutor.execute(this, 'veristand', lvVersions)
diffPipeline(lvVersions[0])