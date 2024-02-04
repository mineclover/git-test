## mvp

[git book](https://git-scm.com/book/en/v2) 기반 merge 순서 테스트

## scene

### default

## todo

- [ ] pull rebase 와 rebase 차이
- [ ] merge와 rebase 차이
- [ ] cherry-pick 와 rebase 차이

## ref

```
힌트: You have divergent branches and need to specify how to reconcile them.
힌트: You can do so by running one of the following commands sometime before
힌트: your next pull:
힌트:
힌트:   git config pull.rebase false  # merge
힌트:   git config pull.rebase true   # rebase
힌트:   git config pull.ff only       # fast-forward only
힌트:
힌트: You can replace "git config" with "git config --global" to set a default
힌트: preference for all repositories. You can also pass --rebase, --no-rebase,
힌트: or --ff-only on the command line to override the configured default per
힌트: invocation.
fatal: Need to specify how to reconcile divergent branches.
```

[Github git pull error (merge, rebase, fast-forward)](https://wooono.tistory.com/692)
