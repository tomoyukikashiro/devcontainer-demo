# devcontainer-demo

- branch [no-devcontainer](https://github.com/tomoyukikashiro/devcontainer-demo/tree/no-devcontainer)
  - devcontainer なしで docker-compose でサンプルアプリを起動するのみ
  - これだと webstorm の補完とか効かないのがわかる
- branch [devcontainer](https://github.com/tomoyukikashiro/devcontainer-demo/tree/devcontainer)
  - no-devcontainer を devcontainer で起動できるように修正したもの
- branch [custom-image-devcontainer](https://github.com/tomoyukikashiro/devcontainer-demo/tree/custom-image-devcontainer)
  - devcontainer で使う image を自分で用意したもの
  - node.js と ruby の両方が欲しい場合などは公式 image がないので、このように用意するとよさそう
- branch [devcontainer-codespace-jetbrain](https://github.com/tomoyukikashiro/devcontainer-demo/tree/devcontainer-codespace-jetbrain)
  - devcontainer を github codespace で起動してローカルの webstorm で編集できるようにしたもの
  - ref https://docs.github.com/ja/codespaces/developing-in-a-codespace/using-github-codespaces-in-your-jetbrains-ide
