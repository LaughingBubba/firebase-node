# firebase-node
docker alpine:node image with firebase-tools installed for deployment for use by Gitlab CI and the like.

## Workflow
- update dockerfile using IDE or vim, nano etc
- build the image ```docker build ./```
- push the GH repo
- As docker hub is linked to this repo the, the DH repo will be updated automagically.