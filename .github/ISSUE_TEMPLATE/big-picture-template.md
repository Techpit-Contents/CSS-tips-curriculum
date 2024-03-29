---
name: bigpicture企画書テンプレート
about: bigpicture企画書のテンプレートです
title: ''
labels: ''
assignees: ''

---


# 企画書：技術の全体像を掴む学習教材
_最小限で受講者への価値を最大化するために、企画書の作成作業を通して、教材のスコープを明確にします。_

## 全体像把握教材の学習目標
_本企画書は、学習者がこれから学ぶ`言語・フレームワーク`について全体像を把握するための内容となっております。
<br>そのため、学習者は本企画書を読むことにより、その`言語・フレームワーク`を使った開発をするうえで必要な技術の概観を知ることができ、スムーズに教材学習に取り組める状態になることを目標としております。</br>_

### 教材のタイトル
- 〇〇の全体像

    ```text
    （例）
     Reactの全体像
    ```

### 対象者
_誰が学ぶか、その企画を学ぶのに適する読者の技術レベルを踏まえて記述してください。_
- 学習対象者

    ```text
    (例)
    ・JavaScriptを使った開発経験がある(個人開発可)。
    ・jQueryやAngularといった他のJavaScriptライブラリやフレームワークでの開発経験がある(個人開発可)。
    ```

### 学習後のゴール
_ここでは、全体像教材を学び終えたあとの学習者の状態について説明してください。_
- 学習後の状態
    
    ```text
    （例）
    ・Reactの技術の全体像を理解して、プロジェクトの初め方を理解している。
    ・次のステップとして、Reactを使った小規模アプリを作れるような段階
    ```

### 企画内容
_学習する言語・フレームワークの全体像を以下を参考に記述してください。_

- `言語・フレームワーク`について　
<br>_その言語・フレームワークが持っている思想・特徴を挙げてください。_</br>

    ```text
    （例）
    ・ユーザーインターフェース構築のためのJavaScriptライブラリ。
    ・宣言的なView、コンポーネントベース、一度学習すればどこでも使えるといった特徴がある。
    ```
    
- `言語・フレームワーク`の歴史
<br>_いつ、誰がorどんな組織が、どのような技術課題を解決するためにその`言語・フレームワーク`が生まれたかの
背景、また現在の開発状況を記述してください。_</br>

    ```text
    （例）
    ・Reactは2011年にFacebookによって開発されたJavaScriptのライブラリ。
    ・2011年後半、Facebook Ads(Facebook広告の管理ツール)のUIにおいて、機能が増えていくことによりコードが複雑になり保守が困難な状況に陥っていた。それを解決するためにFacebookの社員であるJordan Walke氏が、FaxJSというReactのプロトタイプを開発しプロダクトに導入した。
    ・現在はFacabookとオープンソースコミュニティによって開発がおこなわれている。
    ```

- `言語・フレームワーク`の技術的パラダイム
<br>_本教材における`言語・フレームワーク`の技術的パラダイムを説明してください。_</br>
    ```text
    (例)
    ・jQueryなどに代表される命令的UIから宣言的UIがReactから主流になった。
    ```

- `言語・フレームワーク`の代表的な機能
<br>_ここでは、言語・フレームワーク における代表的な機能を説明してください。_</br>
    ```text
    (例)
    ・JSX React要素を生成する、JavaScriptの拡張構文
    ・props 状態を持つコンポーネントをpropsを使うことで作ることができる
    ```

- `言語・フレームワーク`の選択理由
<br>_なぜその`言語・フレームワーク`が選ばれるのか、学ぶべき理由を記述してください。_</br>

    ```text
    （例）
    ・ユーザがUI・UXに求める水準が高くなり、Webフロントエンドで難易度の高い実装を求められるようになったから。 
    ・SPA(Single Page Application)のような動的な処理をするのにjQueryでは負担になってきたから。
    ・virtual DOMを使用していることで、CPUなどのバッテリーを節約できるため、パフォーマンスが優れている。
    ```

- `言語・フレームワーク`を使用するのに適さないユースケース
<br>_学習者とのミスマッチを避けるためにも、ここでは以下のように`言語・フレームワーク`を学ぶのに適さない場合を記述してください。_</br>
    ```text
    （例）
    ・Reactだとコンポーネントを設計する必要があり、早く作ることには向かない。
    ```

- `言語・フレームワーク`の関連技術
<br>_本教材で学習する`言語・フレームワーク`の関連技術を記述してください。_</br>

    ```text
    （例）
    ・　テスト Jest
    ・　デバック React Dev tools
    ・　パッケージマネージャー Yarn npm 
    ・　バンドラ Webpack Parcel
    ・　コンパイラ Babel
    ```

- `言語・フレームワーク`の参考リファレンス
<br>_`言語・フレームワーク`で学習の参考になるリファレンスを説明してください。_</br>
(例)
・ [React公式ドキュメント](https://ja.reactjs.org/)
</br>

- `言語・フレームワーク`の特徴を示すサンプルコードとその解説
<br>_ここでは、学習する`言語・フレームワーク`の特徴的なコードを10行ほどを目安に表示して、コードの解説をしてください。
全体像を学習する段階から学習言語のイメージを掴むといった目的があります。_</br>
    ```javascript
    (コード例)
    import React, { Component } from 'react';

    class App extends Component {
      render() {
        return (
          <h1>Hello world</h1>
        );
      }
    }

    export default App;
    ```

- プロジェクトの始め方
<br>_プロジェクトの始め方を説明してください。実際に開発を始めるのは以降の章で扱うのでここでは、概要を掴むことを目的としています。(そのため、学習者はここではコードを実行しなくてもよいです)_</br>

     ```text
   （例）
    ・新しいReactプロジェクトを始める方法
    node -v
    npx create-react-app my-app
    cd my-app
    npm start
    ```

# チェックリスト
_上記の企画内容がすべて記載されているか確認してください_

- [ ] `言語・フレームワーク`について
- [ ] `言語・フレームワーク`の歴史
- [ ] `言語・フレームワーク`の技術的パラダイム
- [ ] `言語・フレームワーク`の代表的な機能
- [ ] `言語・フレームワーク`の選択理由
- [ ] `言語・フレームワーク`を使用するのに適さないユースケース
- [ ] `言語・フレームワーク`の関連技術
- [ ] `言語・フレームワーク`の参考リファレンス
- [ ] `言語・フレームワーク`のサンプルコードと解説
- [ ] プロジェクトの始め方

