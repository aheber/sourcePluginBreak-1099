Create a scratch org, try and `sfdx force:source:deploy -m LightningComponentBundle` or `sfdx force:source:deploy -u 1099-repro -c -m AuraDefinitionBundle` and it should fail (without a useful warning). Go into the Org and inspect the deployment to see the failure. `An object 'withoutContent' of type LightningComponentBundle was named in package.xml, but was not found in zipped directory`
