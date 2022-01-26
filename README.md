# serverspec-demo-1
serverspec-demo-1は、Serverspecを使用して対象となるAWSのEC2インスタンス上でテストを自動で行います。  
# 使用技術
- ServerSpec
  - Ruby
- AWS
  - VPC
  - EC2
  - RDS
# 構成図
![sample]()  
# 特徴
- テスト内容は、他リポジトリ「ansible-demo」の実行結果を確認するものとなっています。
- 実際にテストをする際は、テストする側のEC2内に他リポジトリ「ansible-demo」と、当リポジトリ「serverspec-demo-1」が入っていることが必要です。
