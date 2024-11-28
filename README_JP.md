![KLC OS Banner](https://github.com/user-attachments/assets/eabf88ec-474a-4e63-99cf-20daafc52f77)

## ソースコードですか? この GSI は Ponces Android 15 AOSP に基づいています

## ビルド

AOSP GSI のビルドを始めるには、[Git とリポジトリ](https://source.android.com/docs/setup/reference/repo)、そして [GSI のビルド方法](https://github.com/phhusson/treble_experimentations/wiki/How-to-build-a-GSI%3F)を理解する必要があります。

メモ: 
- 1 ～ 5 個の項目に注目してください
- これをビルドするには少なくとも 30 GB の RAM が必要です
- 少なくとも 200 GB の空きストレージ (HDD または SSD)
- メモ (Notes.txt) には、ブートアニメーションのロゴとデフォルトの壁紙のパス、および system.img のパスが含まれています。お役に立てば幸いです。
- `KLC_OS/treble_aosp/build.sh` のスクリプトに注目してください。そのにも何かを記しています。
- すべての KLC OS のファイルは KLCStuffs のフォルダ内にあります

### ステップ

1. AOSP ビルド用の新しい作業ディレクトリを作成してそこに移動します: <br />
`mkdir klc_os; cd klc_os`

2. このリポジトリをクローン: <br />
`git clone https://github.com/LoggingNewMemory/KLC_OS -b android15.0`

3. ビルドを開始します。頑張ってください。 <br /> 
`bash KLC_OS/treble_aosp/build.sh`

謝辞:
- [ponces](https://github.com/ponces)
- TrebleDroid Builders Community
- Wahid (サーバーの提供)
