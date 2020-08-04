# Orbs

**Description:**

We have a config file that requires a specific Ruby version be installed, however the image we are using doesn't have Ruby, so the build fails. Utilizing the Ruby Orb (`circleci/ruby`) install Ruby version `2.3.8` so the build will be green.

**Goals:**

- Add the Ruby Orb to the config file
- Install Ruby version `2.3.8` with Orb
- Build should be green if Ruby installed properly

**Help:**
<details>
  <summary>Spoiler warning</summary>
  https://circleci.com/orbs/registry/orb/circleci/ruby#usage-examples
</details>