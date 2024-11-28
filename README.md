# armawxlab

本リポジトリは、SHIFT技術ブログに掲載した Raspberri Pi 5 に AWX 24.6.1 と GitLab CE 17.5.1 を構築する Playbookを格納しています。

## 前提条件

- 構築対象
  - Raspberry Pi 5
  - メモリ 8GB
  - OS Ubuntu 24.04 LTS
- Ansible実行マシン
  - Ansibleバージョン2.14以上

## 使用方法

- inventoryファイルの編集
- setup_all.yml 内の vars 以下を必要に応じて変更
- Playbookを実行

  ```
  $ ansible-playbook -i inventory setup_all.yml
  ```
