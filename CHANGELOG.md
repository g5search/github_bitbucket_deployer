## v1.0.4.rc.1 (2020-05-05)
* making generic so it can be used with other git providers
* callers should include `repo`, `repo_url`, and `branch`
([#7](https://github.com/g5search/github_bitbucket_deployer/pull/7))


## v1.0.3.rc.2 (2020-04-09)
* deleting everything and retrying if we encounter an error anywhere
([#6](https://github.com/g5search/github_bitbucket_deployer/pull/6))

## v1.0.2 (2019-09-06)

* Introducing `force_pristine_repo_dir` flag to 
  `GithubBitbucketDeployer::Git`
  ([#5](https://github.com/g5search/github_bitbucket_deployer/pull/5))

## v1.0.0 (2016-11-04)

* Enhancements to error handling with general refactoring of
  `GithubBitbucketDeployer::Git`
  ([#2](https://github.com/g5search/github_bitbucket_deployer/pull/2))
