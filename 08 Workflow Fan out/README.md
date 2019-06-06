# Fan Out Workflow

**Description:**

The user is building a Node "NPM" module. Before every release they ensure that the module is compatible with the latest version of Node.js, version 8, and version 6. What the user would like to do is have each Node test run concurrently. `build` should run first, then each Node test at the same time, and finally `deploy` should run last.

**Goals:**

- Demonsrate a proper "fan out" workflow with concurrent test.
- Share link to green Workflow.


**Help:**
<details>
  <summary>Spoiler warning</summary>
  * https://circleci.com/docs/2.0/workflows/#fan-outfan-in-workflow-example
</details>
