# Challenge Title

**Description:**

We have a `deploy` job in our Workflow. BUT! We only want our workflow to trigger for a specific set of tags. Edit this workflow so the `deploy` job only runs for tagged commits that match the goals below.

**Goals:**

- Ensure the `deploy` job only runs for tagged commits.
- Any of the following tags should trigger the job: "LTS-main-0.1.1", "beta-main-0.1.1"
- The job `deploy` should NOT run for any of the following tags: "alpha-main-0.1.1", "alpha-secondary-1.0.0"
