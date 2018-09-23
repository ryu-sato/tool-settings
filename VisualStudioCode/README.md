
# 基本設定

[settings.json](master/VisualStudioCode/settings.json)

# インストールする拡張機能

## 開発環境がリモートにある場合に役立つもの

- Remove VSCode
    - localhost に VSCode があるが、リモートサーバにコードがある場合に VSCode を使ってコードを編集できるようにするプラグイン
    - rmate(ssh でコードと VScode 間でセキュア通信を行う) と併用して使う
    - https://marketplace.visualstudio.com/items?itemName=rafaelmaiolla.remote-vscode

## コーディング規約を揃えるために役立つもの

- EditorConfig
    - 設定ファイル .editorconfig でエディタの基本設定を行う
        - 文字コード、改行コード、インデント幅などの共通設定を決める
    - VSCode で EditorConfig の設定に従うための拡張機能をインストールする
        - https://marketplace.visualstudio.com/items?itemName=EditorConfigTeam.EditorConfig

## 開発言語ごとの拡張機能

VSCode 標準での開発言語ごとに説明された拡張機能や設定方法を試すのが良いと思われる。

参考情報：https://code.visualstudio.com/docs の Languages

- PowerShell を使う場合
    - [PowerShell Language Support for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell)
- Ruby を使う場合
    - [Ruby Language and Debugging Support for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby)
    - [Simple Ruby ERB](https://marketplace.visualstudio.com/items?itemName=vortizhe.simple-ruby-erb)
- JavaScript を使う場合
    - [Sublime Babel](https://marketplace.visualstudio.com/items?itemName=joshpeng.sublime-babel-vscode)
    - その他
        - https://code.visualstudio.com/Docs/languages/javascript#_writing-jsconfigjson に従って設定する。
- Java を使う場合
    - [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack) (下記拡張機能が含まれている)
        - [Language Support for Java(TM) by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.java)
        - [Debugger for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-debug)
        - [Java Test Runner](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-test)
        - [Maven Project Explorer](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-maven)
- Groovy を使う場合
    - [GSP Syntax Highlighting](https://marketplace.visualstudio.com/items?itemName=SpankyWorks.groovy-gsp)
- Grails を使う場合
    - [Gradle Language SUpport](https://marketplace.visualstudio.com/items?itemName=naco-siren.gradle-language)
    - Java, Groovy を使う場合の拡張機能
