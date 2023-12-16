# Github Copilot

## 概要
* [githubCopilot公式](https://github.com/features/copilot/)
* [GithubDoc(GithubCopilot)](https://docs.github.com/ja/copilot/overview-of-github-copilot/about-github-copilot-individual)
* プラン（[Copilot Individual と Copilot Business](https://docs.github.com/ja/copilot/overview-of-github-copilot/about-github-copilot-individual#copilot-individual-%E3%81%A8-copilot-business)）
* Individual料金（[①GitHub Copilot の課金について](https://docs.github.com/ja/copilot/overview-of-github-copilot/about-github-copilot-individual#github-copilot-%E3%81%AE%E8%AA%B2%E9%87%91%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6)、[②GitHub Copilot の課金について](https://docs.github.com/ja/billing/managing-billing-for-github-copilot/about-billing-for-github-copilot#github-copilot-%E3%81%AE%E8%AA%B2%E9%87%91%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6)）
    ```quote
    公式Docより抜粋＞
    個人用アカウントで有料サブスクリプションを開始する前に、GitHub Copilot を評価するための 30 日間の 1 回限りの試用版を設定できます。 試用版を開始するには、月単位または年単位の請求期間を選び、支払い方法を指定する必要があります。 30 日以内に試用版をキャンセルしない場合、試用版は自動的に有料サブスクリプションに移行します。 GitHub Copilot の試用版は、30 日間の間いつでもキャンセルすることができ、料金は発生しません。 試用期間が終了する前にキャンセルした場合、30 日間の試用期間が終了するまで、GitHub Copilot に引き続きアクセスできます。
    ```

## 導入方法
* [公式Doc](https://docs.github.com/ja/copilot/getting-started-with-github-copilot)

1. [Visual Studio Code で GitHub Copilot 拡張機能をインストールする](https://docs.github.com/ja/copilot/getting-started-with-github-copilot#visual-studio-code-%E3%81%A7-github-copilot-%E6%8B%A1%E5%BC%B5%E6%A9%9F%E8%83%BD%E3%82%92%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB%E3%81%99%E3%82%8B)

## サブスクリプション解約方法
1. Githubサイトへログインする（[ログイン](https://github.com/)）
2. 右上のプロフィール＞settingをクリック
3. 左側のメニューBilling and plans（請求と計画）＞Plans and usage（計画と使用方法）をクリック
4. Add-ons（アドオン）＞GitHub Copilt＞Cancel trial（使用版をキャンセル）をクリック
5. 本当にキャンセルしてもいいですか？と聞かれるので以下を確認の上、「I understand, cancel GitHub Cpilot trial（わかりました。、GitHub Copilotトライアルをキャンセルします）」をクリック
    ```text
    You will lose access to these benefits
    （これらの特典にアクセスできなくなります）:
    ❌Suggested code completion in most programming languages including Python, JavaScript, TypeScript, Go, and Ruby
    （Python、JavaScript、TypeScript、Go、Rubyを含むほとんどのプログラミング言語でのコード完了の提案）
    ❌Support for VS Code, Visual Studio, Neovim, and JetBrains IDEs
    （VSコード、Visual Studio、Neovim、およびJetBrains IDEのサポート）
    ❌Copilot Chat in the IDE
    （IDEのコパイロットチャット）
    ❌Copilot in the CLI
    （CLIのコパイロット）
    You have 11 days remaining in your 30-day free trial. You can cancel GitHub Copilot without any charges.

    What is your user type?
    ✅Free / Student
    ✅Trial
    ✅Paid

    Which development environment do you use?
    ✅Visual Studio Code
    ✅Visual Studio
    ✅JetBrains
    ✅Neovim

    What programming languages do you ✅usually use?
    ✅Python
    ✅JavaScript
    ✅TypeScript
    ✅Java
    ✅Ruby
    ✅Go
    ✅C#
    ✅Rust
    ✅Html

    What best describes your programming experience?
    ✅Student / Intern learning to program
    ✅0 to 2 years of professional programming experience
    ✅3 to 5 years of professional programming experience
    ✅6 to 10 years of professional programming experience
    ✅11 to 15 years of professional programming experience
    ✅More than 16 years of professional programming experience

    We're sorry that your first experience with copilot did not meet your expectations, Would you tell us why?
    ✅It wasn't clear how to use Copilot
    ✅Copilot is distracting within my development environment
    ✅I found an alternative
    ✅It's too expensive
    ✅I didn't like the quality of the suggestions
    ✅Copilot didn't work well with other extensions
    ✅I have privacy/security concerns
    ✅I have access to copilot through my company

    Do you have other feedback, comments, or suggestions that you want to convey to us?
    ```
6. 完了すると以下メッセージが表示される。
    ```text
    You've cancelled your subscription to GitHub Copilot. This plan change will take effect on 2023-12-25.
    (GitHub Copilot のサブスクリプションをキャンセルしました。このプラン変更は 2023 年 12 月 25 日に発効します。)
    ```