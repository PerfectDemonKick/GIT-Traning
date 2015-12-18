# GIT-Traning
***

## Gitの覚書&練習です。
***
##### * ブランチからファイルを削除
> git rm &lt;fileName&gt;

##### * リモートのブランチをチェックアウトする
> git pull &lt;remote&gt; &lt;localBranch&gt;

##### * リモートのブランチをチェックアウトする
> git pull &lt;remote&gt; &lt;localBranch&gt;

##### * コミットの修正（？）Aを修正しA'を作る。
>commit --amend

###### * HEAD~nで指定したコミットに現在の枝を複製する。
そのとき複製するコミットを選択したり順序変えたりできるっぽい
>git rebase -i HEAD~n

##### * HEADにコミットを複製する。接木的。子がいた場合道ずれにする。
> git cherry-pick &lt;複製したいコミット&gt;

##### * 
> git push origin ブランチ名