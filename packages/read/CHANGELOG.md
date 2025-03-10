# @changesets/read

## 0.4.2

### Patch Changes

- Updated dependencies [[`41e2e3d`](https://github.com/atlassian/changesets/commit/41e2e3dd1053ff2f35a1a07e60793c9099f26997), [`cc8c921`](https://github.com/atlassian/changesets/commit/cc8c92143d4c4b7cca8b9917dfc830a40b5cda20), [`cc8c921`](https://github.com/atlassian/changesets/commit/cc8c92143d4c4b7cca8b9917dfc830a40b5cda20), [`cc8c921`](https://github.com/atlassian/changesets/commit/cc8c92143d4c4b7cca8b9917dfc830a40b5cda20), [`2363366`](https://github.com/atlassian/changesets/commit/2363366756d1b15bddf6d803911baccfca03cbdf), [`41e2e3d`](https://github.com/atlassian/changesets/commit/41e2e3dd1053ff2f35a1a07e60793c9099f26997)]:
  - @changesets/types@1.0.0
  - @changesets/git@1.0.0
  - @changesets/parse@0.3.2

## 0.4.1

### Patch Changes

- Updated dependencies [[`fe0d9192`](https://github.com/atlassian/changesets/commit/fe0d9192544646e1a755202b87dfe850c1c200a3)]:
  - @changesets/git@0.4.0

## 0.4.0

### Minor Changes

- [`bca8865`](https://github.com/atlassian/changesets/commit/bca88652d38caa31e789c4564230ba0b49562ad2) [#221](https://github.com/atlassian/changesets/pull/221) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Added support for reading old changesets from v1

* [`bca8865`](https://github.com/atlassian/changesets/commit/bca88652d38caa31e789c4564230ba0b49562ad2) [#221](https://github.com/atlassian/changesets/pull/221) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Replaced sinceMaster parameter with sinceRef parameter which can be any git ref such as a branch, tag, commit or etc.

### Patch Changes

- Updated dependencies [[`bca8865`](https://github.com/atlassian/changesets/commit/bca88652d38caa31e789c4564230ba0b49562ad2)]:
  - @changesets/git@0.3.0

## 0.3.1

### Patch Changes

- Updated dependencies [[`8f0a1ef`](https://github.com/atlassian/changesets/commit/8f0a1ef327563512f471677ef0ca99d30da009c0)]:
  - @changesets/types@0.4.0
  - @changesets/git@0.2.4
  - @changesets/parse@0.3.1

## 0.3.0

### Minor Changes

- [`8dce96f`](https://github.com/atlassian/changesets/commit/8dce96f8aec43f82b35e65f54b06cbeed3275885) [#187](https://github.com/atlassian/changesets/pull/187) Thanks [@gardnerjack](https://github.com/gardnerjack)! - Added --empty flag to the add command for empty changeset files. New tests for adding, writing, parsing, and reading empty changesets.

### Patch Changes

- Updated dependencies [[`8dce96f`](https://github.com/atlassian/changesets/commit/8dce96f8aec43f82b35e65f54b06cbeed3275885)]:
  - @changesets/parse@0.3.0

## 0.2.2

### Patch Changes

- [89c0894](https://github.com/atlassian/changesets/commit/89c08944fac84f71241305e359e9717ad4ec1b62) [#167](https://github.com/atlassian/changesets/pull/167) Thanks [@Noviny](https://github.com/Noviny)! - Fix broken `sinceMaster` arg - which was not working with v2 changesets

- Updated dependencies [89c0894]:
  - @changesets/git@0.2.2

## 0.2.1

### Patch Changes

- [8c43fa0](https://github.com/atlassian/changesets/commit/8c43fa061e2a5a01e4f32504ed351d261761c8dc) [#155](https://github.com/atlassian/changesets/pull/155) Thanks [@Noviny](https://github.com/Noviny)! - Add Readme

* [0320391](https://github.com/atlassian/changesets/commit/0320391699a73621d0e51ce031062a06cbdefadc) [#163](https://github.com/atlassian/changesets/pull/163) Thanks [@Noviny](https://github.com/Noviny)! - Reordered dependencies in the package json (this should have no impact)

* Updated dependencies [8c43fa0, 0320391, 1ff73b7]:
  - @changesets/git@0.2.1
  - @changesets/parse@0.2.1
  - @changesets/types@0.3.0

## 0.2.0

### Minor Changes

- [296a6731](https://github.com/atlassian/changesets/commit/296a6731) - Safety bump: Towards the end of preparing changesets v2, there was a lot of chaos - this bump is to ensure every package on npm matches what is found in the repository.

### Patch Changes

- Updated dependencies [296a6731]:
  - @changesets/git@0.2.0
  - @changesets/parse@0.2.0
  - @changesets/types@0.2.0

## 0.1.2

### Patch Changes

- [a15abbf9](https://github.com/changesets/changesets/commit/a15abbf9) - Previous release shipped unbuilt code - fixing that

## 0.1.0

### Minor Changes

- [6d119893](https://github.com/changesets/changesets/commit/6d119893) - Initial Release

- Updated dependencies [c46e9ee7]:
- Updated dependencies [519b4218]:
  - @changesets/git@0.1.0
  - @changesets/parse@0.1.0
  - @changesets/types@0.1.0
