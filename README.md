# python-vagrant-ansible

vagrantとansibleの練習。  
pyenvが導入されたdebianの環境を作成する。  

playbookのネタ元：https://github.com/pypeach/pypeach_playbook

## コマンド

### 仮想マシン起動

```vagrant up```

初回の起動時はansibleによるprovisionが行われる。

### 停止

```vagrant halt```

### 破棄

```vagrant destroy```
