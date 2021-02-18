<!--
Not all PRs will require all tests to be carried out. Delete where appropriate.
-->

<!--
@team-halo-engineers will be automatically requested for review once
this PR has been submitted. (But not for drafts)
-->

This PR:

- adds/changes/removes etc

### Testing

Description on how keda can be tested.

- [ ] fresh install works
  - [ ] AWS
  - [ ] Azure
  - [ ] KVM
- [ ] upgrade from previous version works
  - [ ] AWS
  - [ ] Azure
  - [ ] KVM

#### Other testing

Description of features to additionally test for keda installations.

- [ ] check reconciliation of existing resources after upgrading
- [ ] X still works after upgrade
- [ ] Y is installed correctly

<!--
Changelog must always be updated.
-->

### Checklist

- [ ] Update changelog in CHANGELOG.md.
- [ ] Make sure `values.yaml` and `values.schema.json` are valid.
- [ ] Add the `crd-install` mechanism if this PR (1) changes CRD definitions and (2) the `crd-install` mechanism is not in place
