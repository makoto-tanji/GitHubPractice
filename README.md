# GitHubPractice

GitHubのコマンドや流れを理解するための勉強内容

# directory

./
├────test<br>
|<span>       </span>├────.git<br>
|<span>       </span>├────process.txt<br>
|<span>       </span>└────README.md<br>
|<br>
└────clone<br>
<span>       </span>├────process.txt<br>
<span>       </span>└────README.md<br>

# Usage

```bash
git init
git add -A
git commit -m "first-commit"
git remote add origin https://github.com/makoto-tanji/GitHubPractice.git
git push -u origin main
```

edit

```bash
git add -A
git commit -m "edited content"
git push
```

# command

## branch

ブランチ作成
```bash
git branch testBranch
```

ブランチ確認
```bash
git branch
```

ブランチ切り替え
```bash
git checkout testBranch
```

ブランチをマージ
```bash
git checkout main
git branch
git merge testBranch
```

ブランチ削除
```bash
git branch -d testBranch
git branch
```

## clone

クローン
```bash
git clone https://github.com/<ユーザー名>/<リポジトリ名>.git  <ディレクトリ>
git clone https://github.com/makoto-tanji/GitHubPractice.git ./
```



```bash
```


# Note

## branch

main<span>       </span>testBranch

1-1<br>
|<br>
|<br>
1-2<br>
|<br>
├───────┐<br>
1-3<span>       </span>2-1<br>
|<span>       </span>|<br>
|<span>       </span>|<br>
1-4<span>       </span>2-2<br>
|<span>       </span>|<br>
├───────┘<br>
1-5

## clone

main<span>       </span>clone

1-5<br>
|<br>
|<br>
├───────┐<br>
|<span>       </span>3-1<br>
|<span>       </span>|<br>
|<span>       </span>|<br>
|<span>       </span>3-2<br>
|<span>       </span>|<br>
├───────┘<br>
1-6<br>