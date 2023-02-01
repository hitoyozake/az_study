# ARM(Azure Resource Manager)
Azure Resoure Managerをダウンロード，エクスポート，中身の確認をしたい時はResource Groupから行う．わざわざVMとかを開かなくて良い．
ARMを使えばマシンの複製や，複製してカスタマイズするなどがjsonで行える.


# VMの可用性セットを組んでいる場合，設定を変えるには全部のVMを止めないとだめ
 - VMにネットワークカードを追加する時はVMを停止する必要がある

# 新しいVMを作り，自動的にVMをセットアップするためのpowershellのスクリプトを作った場合，SetupComplete.cmd batchファイルを %windir%/setup/scripts に置く