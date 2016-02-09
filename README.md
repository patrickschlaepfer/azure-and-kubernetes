# azure-and-kubernetes

It's about set up a kubernetes cluster on an azure cloud, from windows system.

## Prerequisites

Get a Azure account

Get the microsoft azure cli package
https://azure.microsoft.com/en-us/documentation/articles/xplat-cli-install/

Somehow it's not that clear, that you still need to get node.js too. So, yes you have to get it here at Nodejs.org

If you don't have git installed, download it too.

After installing azure cli package you have to reboot your machine.

Cloning kubernetes

git clone https://github.com/kubernetes/kubernetes

cd kubernetes/docs/getting-started-guides/coreos/azure/

npm install

## Setting subscription

It's also important to set the environment variable AZ_SUBSCRIPTION

set AZ_SUBSCRIPTION=xxx-yyy-yyyyyyy


