# @roadiehq/backstage-plugin-aws-backend

## 1.1.0

### Minor Changes

- 015aebdf: Bump plugins version to be compatible by backstage 1.7

## 1.0.5

### Patch Changes

- eaa0bb2: update dependencies

## 1.0.4

### Patch Changes

- 151b46b: bump to latest backstage package versions

## 1.0.3

### Patch Changes

- c9cfaad: Release all plugins after fixing typescript exports issue.

## 1.0.2

### Patch Changes

- 86eca6a: Update dependencies

## 1.0.1

### Patch Changes

- 55c9711: update depdendencies

## 1.0.0

### Major Changes

- 40997a1: initial release of the plugin

### Patch Changes

- 6b4cc16: Update dependencies
  Add package information to the package.jsons, to tell the backstage cli how to run the tests

## 0.0.3

### Patch Changes

- e2a86ee: Adds initial versions of @roadiehq/catalog-backend-module-aws, @roadiehq/backstage-plugin-aws and @roadiehq/backstage-plugin-aws-backend.

  @roadiehq/catalog-backend-module-aws exposes entity provider classes to injest S3 Buckets, Lambda Functions and IAM users into the entity catalog.

  @roadiehq/backstage-plugin-aws-backend provides a generic API to retrieve AWS resources using the CloudControl API.

  @roadiehq/backstage-plugin-aws provides entity component cards to display details about S3 Buckets, Lambda Functions and IAM users.

- e1e99d9: Use a consistent version dependency of aws-sdk across the repository.
