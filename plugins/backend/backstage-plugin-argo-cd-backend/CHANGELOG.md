# @roadiehq/backstage-plugin-argo-cd-backend

## 2.6.0

### Minor Changes

- 015aebdf: Bump plugins version to be compatible by backstage 1.7

## 2.5.3

### Patch Changes

- eaa0bb2: update dependencies

## 2.5.2

### Patch Changes

- 231f37e: Added logging to improve visibility

## 2.5.1

### Patch Changes

- e017302: 1. Get Application App Data has a changed thrown error message. 2. Failing on a wider spectrum of error messages when deleting projects. If you were expecting a false when the project failed to delete for these other possible reasons, now the function will throw for those other possible reasons. 3. Logging thrown errors for the endpoints that create an argo configuration, or delete an argo configuration. 4. Added unit tests.

## 2.5.0

### Minor Changes

- 8716dfb: Use different credentials for each instance

## 2.4.4

### Patch Changes

- 151b46b: bump to latest backstage package versions

## 2.4.3

### Patch Changes

- c9cfaad: Release all plugins after fixing typescript exports issue.

## 2.4.2

### Patch Changes

- 86eca6a: Update dependencies

## 2.4.1

### Patch Changes

- 55c9711: update depdendencies

## 2.4.0

### Minor Changes

- 16d70f0: Use `cross-fetch` instead of `axios` for rest requests.

## 2.3.0

### Minor Changes

- 9bcaa85: bug fix: read label value being passed in instead of using app name

## 2.2.0

### Minor Changes

- 4259734: fix: argocd sync wasn't being sent as an object but rather a string

## 2.1.1

### Patch Changes

- 6b4cc16: Update dependencies
  Add package information to the package.jsons, to tell the backstage cli how to run the tests

## 2.1.0

### Minor Changes

- 3ba9cb9: - Add create endpoints
  - Add delete endpoints
  - Add sync endpoints
  - Add scaffolder action for create

## 2.0.0

### Major Changes

- df841f0: Update dependecies to follow latest upstream version. Removed deprecated props of type 'Entity' passed into components as it is grabbed from context instead.

## 1.3.0

### Minor Changes

- f0421b4: Bumped to the latest upstream packages versions

## 1.2.10

### Patch Changes

- f5cd7e4: Update dependencies to latest Backstage packages

## 1.2.9

### Patch Changes

- 46b19a3: Update dependencies

## 1.2.8

### Patch Changes

- c779d9e: Update dependencies

## 1.2.7

### Patch Changes

- 7da7bfe: Update dependencies

## 1.2.6

### Patch Changes

- ee81868: Update dependencies

## 1.2.5

### Patch Changes

- 5ae1b4b: Update README.md files

## 1.2.4

### Patch Changes

- b5db653: Update dependecies to latest packages

## 1.2.3

### Patch Changes

- a02dbf5: Migrating to TestApiProvider in the tests

## 1.2.2

### Patch Changes

- 49abec7: Update patch to release new changes.

## 1.2.1

### Patch Changes

- a728fd1: Update underlying packages and release.

## 1.2.0

### Minor Changes

- ed90f25: Breaking dependency updates for @backstage/core-app-api, @backstage/test-utils, @backstage/core-plugin-api, @backstage/backend-common && @backstage/integration

## 1.1.1

### Patch Changes

- 773692a: Change default port of backend from 7000 to 7007.

  This is due to the AirPlay Receiver process occupying port 7000 and preventing local Backstage instances on MacOS to start.

## 1.1.0

### Minor Changes

- 1d256c6: Support multiple Argo instances using the app-selector annotation
