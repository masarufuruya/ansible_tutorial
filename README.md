
## 使用方法

### 1. リポジトリをclone

```
git clone git@github.com:masarufuruya/ansible_tutorial.git
```

### 2. 仮想マシンの作成

本リポジトリをダウンロードした場所(Vagrantfileが存在する階層)で、以下のコマンドを実行します。
初回はイメージのダウンロード・セットアップが行われるため、数分程度の時間がかかります。

```
cd ansible_tutorial
vagrant plugin install vagrant-vbguest
vagrant up
```
