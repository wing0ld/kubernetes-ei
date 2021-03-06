# Simplified setup for WSO2 kubernetes Enterprise Integrator

## Contents
* Prerequisites

* Quick Start Guide

## Prerequisites
* Install [Kubernetes  Client](https://kubernetes.io/docs/tasks/tools/install-kubectl/) in order to run the steps provided in the following quick start guide.
* An already setup Kubernetes cluster. If you are unfamiliar with this context, you can use [this guide](https://kubernetes.io/docs/setup/pick-right-solution/) to set up the cluster.
* WSO2 subscribed users can run **wso2ei-latest.sh** with latest updates by providing their subscription username and password. If you do not possess an active WSO2 subscription already, run **wso2ei-ga.sh** which does not require subscription credentials.

## Quick Start Guide
1. Download simplified kubernetes setup for WSO2 Enterprise Integrator(either **wso2ei-latest.sh** or **wso2ei-ga.sh**).From this point forward the steps are being described for wso2ei-latest.sh. If you have downloaded wso2ei-ga.sh please substitute wso2ei-latest.sh with wso2ei-ga.sh for every command.  

2. In the command line, move into the directory where you have downloaded the simplified kubernetes-apim setup. (Usually, the file would be in the “Downloads” directory unless you have changed the default directory to somewhere else.)
3. Provide permissions for the setup file to execute by running **chmod +x wso2ei-latest.sh**
4. Run **./wso2ei-latest.sh --deploy** on your terminal. This will deploy WSO2 Enterprise Integrator in your cluster.

5. Try navigating to https://< NODE-IP >:30443/carbon/ your favourite browser using username: admin and password: admin. Your < NODE-IP > will be provided at the end of the deployment.
6. We welcome you to try out WSO2 Enterprise Integrator by following **[WSO2 Enterprise Integrator- Quick Start Guide](https://docs.wso2.com/display/EI640/Quick+Start+Guide)**.
