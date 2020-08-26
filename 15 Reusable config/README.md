# Reusable config

**Description:**

This config makes use of "Reusable config". Rather than specifying a Docker image or a machine VM, a custom executor of `custom-node` is used. This will need to be defined as the `circleci/node` Docker image. There also seems to be a custom command to generate a log file, but it seems the log file isn't where we expect by default.

**Goals:**

- Define a docker image of `circleci/node` for the `custom-node`executor.
- Without modifying the source of the custom "generatelog" command, resolve the issue to get a green build.
- Share link to green job.

**Help:**
<details>
  <summary>Spoiler warning</summary>
  * https://circleci.com/docs/2.0/reusing-config/#authoring-reusable-commands
</details>