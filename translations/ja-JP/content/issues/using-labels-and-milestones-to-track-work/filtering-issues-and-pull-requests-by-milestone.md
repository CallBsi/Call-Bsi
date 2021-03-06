---
title: Issue とPull Requestをマイルストーンでフィルタリングする
intro: 'Issue およびPull Requestを、関連付けられたマイルストーンに基づいてフィルタリングできます。 [Issue やPull Requestをマイルストーンと関連付ける](/articles/associating-milestones-with-issues-and-pull-requests) と、それらのマイルストーンに基づいて項目を検索できます。 マイルストーン内で Issue およびPull Requestに優先順位を付けることができます。'
redirect_from:
  - /github/managing-your-work-on-github/tracking-the-progress-of-your-work-with-milestones/filtering-issues-and-pull-requests-by-milestone
  - /articles/filtering-issues-and-pull-requests-by-milestone
  - /github/managing-your-work-on-github/filtering-issues-and-pull-requests-by-milestone
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Pull requests
shortTitle: マイルストーンでフィルタ
---

{% tip %}

**参考:**

- 検索バーを使用して Issue とPull Requestをフィルタリングしたい場合は、マイルストーンの検索構文を使用できます。 My Milestone という名前のマイルストーンであれば、検索構文は `milestone:"My Milestone"` となります。
- フィルタの選択をクリアするには、[**Clear current search query, filters, and sorts**] をクリックします。
-  {% data variables.product.prodname_cli %} を使用して Issue またはPull Requestをフィルタすることもできます。 詳しい情報については、ドキュメントの「[`gh issue list`](https://cli.github.com/manual/gh_issue_list)」または「[`gh pr list`](https://cli.github.com/manual/gh_pr_list)」{% data variables.product.prodname_cli %} を参照してください。

{% endtip %}

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.sidebar-issue-pr %}
3. [**Milestones**] を選択して、リポジトリで使用可能なすべてのマイルストーンのリストを表示します。 ![[Milestones] ボタン](/assets/images/help/issues/issues_milestone_button.png)
4. 対象のマイルストーンをリストから選択します。 関連付けられたすべての Issue やPull Requestなどのマイルストーンの関連情報を、マイルストーンのページで確認できます。 詳しい情報については、「[マイルストーンについて](/articles/about-milestones)」を参照してください。

## 参考リンク

- "[Filtering and searching issues and pull requests](/issues/tracking-your-work-with-issues/filtering-and-searching-issues-and-pull-requests)"
- 「[プロジェクトボードでカードをフィルタリングする](/articles/filtering-cards-on-a-project-board)」
