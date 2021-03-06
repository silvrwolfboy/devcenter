ワークフロー エディタ
# 任意のシナリオのワークフローを作成します

## GitFlow
開発用のGItFlowを使用すると、ワークフローの個別の作成や、ブランチでの開発、実行するテストの種類や、特定のテスターグループに展開するアプリケーションのバージョンを簡単に指定する事ができます。

## White label apps
あなたの White label apps に、様々なアプリケーションフレーバ専用のワークフローを作成する事ができます。

## クロスプラットフォーム
iOSとAndroid専用のワークフローを作成し、それぞれの環境を整えましょう。

## ワークフロー特有のスタック
テストを実行するにはワークフローに異なるスタックを定義します。これは、Xcodeの最新版(beta含む)が出てきた際、プロジェクト全体を移行する前に全体をテストしたい時に非常に役立ちます。

ブログをもっと見る

———

# ビルドする際の条件を設定します
## Code push
特定のブランチがアップデートされた時。

## Pull request
プルリクエストをマージする前にコードをテストをしてください。 Bitriseでは、プルリクエストのソースブランチとターゲットブランチを指定し、自動的にGitHub、Bitbucket、GitLabにビルドステータスを返すことができます。

## Tags
リポジトリにタグを追加するときに何が起こるべきかを定義します。

ドキュメントを確認する

———

# 安全なファイルストレージ
## シークレット環境変数
シークレットは暗号化されて保存され、ビルド中またはUIを公開するときにのみ公開されます。接続されたサービスの資格情報とAPIキーは安全です。

## ファイルの保護
プロビジョニング・プロファイル、証明書または保護されたキーストアなど、秘密のenvまたはファイルを設定できます。保護された秘密はUI上に公開することはできず、そのファイルはあなたのチームの誰もダウンロードすることはできません

———

# 同じ設定をローカルで実行する
`bitrise.yml` をダウンロードし、オープンソースのCLIをローカルで使用して、デバッグしたり、端末からオートメーションを実行したりしてください。Bitriseは各ビルドの設定状態を保存し、変更された場合は、古いバージョンと新しいバージョンの差分を確認することができます。ちなみに、以前のバージョンにロールバックするには、[復元]をクリックします。 

CLIについての詳細

———

# 一緒にワークフローのチェーンを見ましょう
パイプラインの繰り返しステージのワークフローを指定し、シームレスに接続します。 UI上のすべてのワークフローチェーンを一目で見ることができます。

———

# 180以上の統合が可能
ライブラリの手順を使用して強力なワークフローを作成します。統合が欠けている場合は、オープンソースライブラリに追加してください。

## スクリプティング
あなたはスクリプトを書くことができますが、しかしそれをする必要はありません。ワークフロー内の任意の場所にScriptステップを挿入し、コマンドを実行するか、必要なツールをインストールします。仮想マシンは完全に制御できるので心配しないでください。

———

# オープンソース
YAMLにラインを追加するのがあなたのスタイルにと合わない場合は、オープンソースエディタをダウンロードしてデスクトップ上にワークフローを設定することもできます。

GitHubのソースコードを確認する

———

もうお分かりですね？
# 今すぐ申し込む - 後でプランを選択する
周りの人を見てみましょう。あなたにも完璧な設定が見つかるはずです！
無料トライアルに申し込む
