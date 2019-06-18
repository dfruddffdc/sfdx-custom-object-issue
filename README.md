1. Authenticate with a DevHub
1. `sfdx force:org:create -f config/project-scratch-def.json -a custom-object-issue`
1. `sfdx force:source:push -u custom-object-issue`
1. `sfdx force:org:open -u custom-object-issue -p lightning/setup/SecuritySharing/home`
