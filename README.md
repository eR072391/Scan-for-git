# Scan-for-git

link(https://medium.com/@levshmelevv/10-000-bounty-for-exposed-git-to-rce-304c7e1f54)

## install 
amass  
オープンソースの情報収集と積極的な偵察技術を使用して、攻撃対象領域のネットワーク マッピングと外部資産の検出を実行します。  
ここではサブドメインの列挙に使用します。  
https://github.com/OWASP/Amass/releases

aquatone  
多数のホストにまたがる Web サイトを視覚的に検査するためのツールであり、HTTP ベースの攻撃対象領域の概要をすばやく把握するのに便利です。  
https://github.com/michenriksen/aquatone/releases

nuclei  
テンプレートに基づいてターゲット全体にリクエストを送信するために使用され、誤検知をゼロにし、多数のホストで高速スキャンを提供します。 Nuclei は、TCP、DNS、HTTP、SSL、ファイル、Whois、Websocket、ヘッドレスなど、さまざまなプロトコルのスキャンを提供します。強力で柔軟なテンプレートを使用して、Nuclei を使用してあらゆる種類のセキュリティ チェックをモデル化できます。  
https://github.com/projectdiscovery/nuclei/releases

pip3 install git-dumper


## Usage
./scan domain.com
