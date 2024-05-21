# Perseus Build
此儲存庫範本將允許您使用 Github Actions 建立 Perseus。 這將幫助那些不想在電腦上設置建置環境的人。

## Azur Lane regions
- **EN**: com.YoStarEN.AzurLane
- **JP**: com.YoStarJP.AzurLane
- **KR**: kr.txwy.and.blhx
- **TW**: com.hkmanjuu.azurlane.gp

## Notes
- 該腳本將從 APKPure 下載最新的基礎 apk。
- 在**無情況**下，任何 APK 都會上傳到此儲存庫以避免 DMCA。
- 如果您想做出貢獻，請分叉該儲存庫

## How to setup
1. 使用此儲存庫作為範本建立新的 PRIVATE 儲存庫 ([Guide](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)).
2. 前往新建立的儲存庫 Settings > Actions > General > Workflow permissions > Set Read and Write permission.
3. Profits!

## How to build
1. Go to Actions -> All workflows -> Perseus Build
2. 使用所需區域運行工作流程
3. 從 Releases 下載 APK
