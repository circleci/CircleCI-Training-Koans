# Matrix Builds

**Description:**

We want to run our job across multiple versions of Node and on both Mac and Linux. Utilize Matrix builds to accomplish this without adding a job for each setup.

**Goals:**

- Add a matrix condition to run the jobs for both `linux` and `macos`
- Add a matrix condition to run the jobs for the following node versions: `10.9.0`,`11.9.0`,`12.9.1`,`13.9.0`
- Share link to green build that executed all 8 jobs, should look like this:

![matrix](/12%20Matrix%20Builds/src/matrix.png)

**Help:**
<details>
  <summary>Spoiler warning</summary>
	* https://circleci.com/docs/2.0/configuration-reference/#matrix-requires-version-21
</details>