# Upload content
アップロードしたコンテンツを保管・配信するバケットとディストリビューション

## 使い方

1. `aws cloudformation deploy --template-file formation.yml --stack-name [your stack name] --capabilities CAPABILITY_IAM --parameter-overrides DomainName=[file domain name] CertificateArn=[cloudfront certificate]`する
2. しばらく待つ
