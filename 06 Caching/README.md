# Caching

**Description:**

We want to speed up our builds and we heard about this concept of "caching". We need to start storing a cache of our `package.json` so that it can be restored in subsequent builds.

In addition we need to know what to do if we need to force a new save of the cache.

**Goals:**

- Uncomment out the `save_cache` and `restore_cache` steps
- Update the `key` of each of those to point at the proper file
- Push up a commit where you find it successfully saves the cache (should see something like this on the step):

```
Creating cache archive...
Uploading cache archive...
Stored Cache to yarn-packages-v1-qwa_N++0aXeaXlpPu1TzrRMKJU1V7n3NYN+0BxBVg20=
  * /home/circleci/.cache/yarn
```

- Push another commit and confirm the cache is restored/used (should see something like this):

```
Found a cache from build 44 at yarn-packages-qwa_N++0aXeaXlpPu1TzrRMKJU1V7n3NYN+0BxBVg20=
Size: 160 B
Cached paths:
  * /home/circleci/.cache/yarn

Downloading cache archive...
Validating cache...

Unarchiving cache...
```

- Finally make the neccesary edits to the config to 'bust' or 'clear' the cache so it doesn't use the existing saved cache and instead stores a new one.

**Help:**
<details>
  <summary>Spoiler warning</summary>
  https://circleci.com/docs/2.0/caching/
  https://circleci.com/docs/2.0/yarn/#caching
  https://circleci.com/docs/2.0/caching/#clearing-cache
</details>