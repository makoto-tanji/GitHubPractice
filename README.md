# GitHubPractice

GitHubのコマンドや流れを理解するための勉強内容

# directory
```
./
 ├────test
 |     ├────.git
 |     ├────process.txt
 |     └────README.md
 |
 └────clone
       ├────process.txt
       └────README.md
```

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
```
main    testBranch
1-1
 |
 |
1-2
 |
 ├───────┐
1-3     2-1
 |       |
 |       |
1-4     2-2
 |       |
 |       |
 |      2-3
 ├───────┘
1-5
```

## clone
```
main    clone
1-5
 |
 |
 ├───────┐
 |      3-1
 |       |
 |       |
 |      3-2
 |       |
 ├───────┘
1-6
```