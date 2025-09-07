# Branch Protection Settings

## Main Branch Protection Rules:
-  Require pull request reviews before merging
-  Require status checks to pass before merging
-  Require conversation resolution before merging
-  Include administrators
-  Restrict who can dismiss reviews

## Required Status Checks:
-  test-matrix (ubuntu-3.8)
-  test-matrix (ubuntu-3.9)
-  test-matrix (windows-3.8)
-  test-matrix (windows-3.9)
-  docker-ci
-  helm-ci