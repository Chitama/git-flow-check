# git-flow-check

```
git flow release start 1.0.0 -> ここは初回のみ
# バージョン番号の更新
git commit -am "1.0.1"
git flow release finish 1.0.0
♯ この操作でdevelopからmainブランチにマージされてタグがつけられる
git push
```