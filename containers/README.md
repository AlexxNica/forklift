# Foreman on OpenShift

## NOTE: THIS IS NOT FOR PRODUCTION (yet)

The following is currently a proof of concept for running Foreman, Katello and the backend systems on OpenShift. This currently uses repository forks with patches, as well as security and data persistence compromises to achieve this. There is a list of to-dos at the bottom of this README that outlines next steps to get this closer to both production and developer readiness.

Caveats:

 * running without any SSL
 * using forks of some repositories due to needed functionality for this to work
 * currently using experimental secrets support in ansible-container
   -- https://github.com/ansible/ansible-container/pull/612

Table of Contents

 * [Setup and Install](./docs/setup-and-install.md)
 * [Architecture](./docs/architecture.md)
 * [Issues to be Addressed](#issues)

For diagrams outlining the architecture, please see the diagrams in the `docs/` folder.
