# Branch Filters

**Description:**

We have a `deploy` job in our Workflow. We have decided we only ever want to run our `deploy` job when we commit to the `production` branch

**Goals:**

- Ensure the `deploy` job only runs for tagged commits.
- Any of the following tags should trigger the job: "beta-main-0.1.1", "beta-secondary-0.1.1"
- The job `deploy` should NOT run for any of the following tags: "alpha-main-0.1.1", "alpha-secondary-1.0.0"
- Create the required branch and meet the requirements above for a green Workflow.
- Share link to green Workflow.

**Help:**
<details>
  <summary>Spoiler warning</summary>
  * https://circleci.com/docs/2.0/workflows-overview/
</details>