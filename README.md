# wptest


## 使い方

以下の項目に従い編集をしてdocker-compose up -d で起動

 - https-portal の environment の STAGE: 'production' はコメントアウトする。
 - portalsite.hyakusho.life を適宜変更
 - SakuraのVPSの場合Firewallで80/433ポートを開ける。これはコントロールパネルのパケットフィルターから操作しないとだめで、ホストマシンでufwとかiptableとか頑張っても無駄だった。
 - SSL証明書がもらえたらコメントをはずす。
 - 終わり。

