## Git Commit Hooks
A collection (sparse :( ) of git commit hooks

## Overview
- pre-commit.k8sssecrets : useful in keeping Kubernetes manifests of kind "Secret" out of your commits

See script body for implementation.  You will have to rename to remove the 'dot' extension.  For example, in the case of `pre-commit.k8sssecrets`, rename to `pre-commit` so that it is triggered by git in the pre-commit stage.
