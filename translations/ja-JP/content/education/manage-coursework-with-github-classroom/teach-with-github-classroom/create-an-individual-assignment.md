---
title: 個人課題の作成
intro: コースにおいて、個人で修了するための課題を学生のために作成できます。
versions:
  fpt: '*'
permissions: 'Organization owners who are admins for a classroom can create and manage individual assignments for a classroom. {% data reusables.classroom.classroom-admins-link %}'
redirect_from:
  - /education/manage-coursework-with-github-classroom/creating-an-individual-assignment
  - /education/manage-coursework-with-github-classroom/create-an-individual-assignment
shortTitle: 個人課題
---

## 個人課題について

{% data reusables.classroom.assignments-individual-definition %}

{% data reusables.classroom.classroom-creates-individual-repositories %}

{% data reusables.classroom.about-assignments %}

個人課題作成の方法を説明する動画については、「[{% data variables.product.prodname_classroom %}の設定の基本](/education/manage-coursework-with-github-classroom/basics-of-setting-up-github-classroom)」を参照してください。

{% data reusables.classroom.reuse-assignment-link %}

## 必要な環境

{% data reusables.classroom.assignments-classroom-prerequisite %}

## 課題を作成する

{% data reusables.classroom.assignments-guide-create-the-assignment %}

## 課題の基本情報をセットアップする

課題に名前を付け、期限を設定するかを決定し、課題リポジトリの可視性を選択します。

- [課題に名前を付ける](#naming-an-assignment)
- [課題に期限を設定する](#assigning-a-deadline-for-an-assignment)
- [課題のタイプを選択する](#choosing-an-assignment-type)
- [課題リポジトリの可視性を選択する](#choosing-a-visibility-for-assignment-repositories)

### 課題に名前を付ける

個人課題では、{% data variables.product.prodname_classroom %}はリポジトリのプレフィックスと学生の{% data variables.product.product_name %}ユーザ名から、リポジトリに名前を付けます。 デフォルトでは、リポジトリのプレフィックスが課題のタイトルとなります。 たとえば、課題に「assignment-1」と名付け、学生の{% data variables.product.product_name %}ユーザ名が「@octocat」である場合、「@octocat」の課題リポジトリ名は「`assignment-1-octocat`」となります。

{% data reusables.classroom.assignments-type-a-title %}

### 課題に期限を設定する

{% data reusables.classroom.assignments-guide-assign-a-deadline %}

### 課題のタイプを選択する

[Individual or group assignment] の下で、ドロップダウンメニューを選択し、[**Individual assignment**] をクリックします。 課題の作成後は、課題タイプを変更できません。 グループ課題を作成する場合は、[グループ課題の作成](/education/manage-coursework-with-github-classroom/create-a-group-assignment)」を参照してください。

### 課題リポジトリの可視性を選択する

{% data reusables.classroom.assignments-guide-choose-visibility %}

{% data reusables.classroom.assignments-guide-click-continue-after-basics %}

## スターターコードを追加し、開発環境を構成する

{% data reusables.classroom.assignments-guide-intro-for-environment %}

- [テンプレートリポジトリを作成する](#choosing-a-template-repository)
- [Choosing an integrated development environment (IDE)](#choosing-an-integrated-development-environment-ide)

### テンプレートリポジトリを作成する

デフォルトでは、新しい課題ではクラスルームの名簿に掲載されている各学生に対し、空のリポジトリが作成されます。 {% data reusables.classroom.you-can-choose-a-template-repository %}

{% data reusables.classroom.assignments-guide-choose-template-repository %}

{% data reusables.classroom.assignments-guide-click-continue-after-starter-code-and-feedback %}

### Choosing an integrated development environment (IDE)

{% data reusables.classroom.about-online-ides %}詳しい情報については、「[{% data variables.product.prodname_classroom %} と IDE の統合](/education/manage-coursework-with-github-classroom/integrate-github-classroom-with-an-ide)」を参照してください。

{% data reusables.classroom.classroom-codespaces-link %}

{% data reusables.classroom.assignments-guide-choose-an-online-ide %}

## 課題にフィードバックを行う

必要に応じて、課題を自動的に採点し、各提出物を学生と議論するための場を作成できます。

- [課題を自動的にテストする](#testing-assignments-automatically)
- [フィードバックのためにプルリクエストを作成する](#creating-a-pull-request-for-feedback)

### 課題を自動的にテストする

{% data reusables.classroom.assignments-guide-using-autograding %}

### フィードバックのためにプルリクエストを作成する

{% data reusables.classroom.you-can-create-a-pull-request-for-feedback %}

{% data reusables.classroom.assignments-guide-create-review-pull-request %}

{% data reusables.classroom.assignments-guide-click-create-assignment-button %}

## 学生を課題に招待する

{% data reusables.classroom.assignments-guide-invite-students-to-assignment %}

You can see whether a student has joined the classroom and accepted or submitted an assignment in the **Classroom roster** tab for the assignment. You can also link students' {% data variables.product.prodname_dotcom %} aliases to their associated roster identifier and vice versa in this tab. {% data reusables.classroom.assignments-to-prevent-submission %}

<div class="procedural-image-wrapper">
  <img alt="個人課題" class="procedural-image-wrapper" src="/assets/images/help/classroom/assignment-individual-hero.png">
</div>

## Monitoring students' progress
The assignment overview page provides an overview of your assignment acceptances and student progress. You may have different summary information based on the configurations of your assignments.

- **Rostered students**: The number of students on the Classroom's roster.
- **Added students**: The number of {% data variables.product.prodname_dotcom %} accounts that have accepted the assignment and are not associated with a roster identifier.
-  **Accepted students**: The number of accounts have accepted this assignment.
-  **Assignment submissions**: The number of students that have submitted the assignment. Submission is triggered at the assignment deadline.
-  **Passing students**: The number of students currently passing the autograding tests for this assignment.

## 次のステップ

- 課題を作成した後、学生はGitおよび{% data variables.product.product_name %}の機能を使用して課題を開始できます。 学生はリポジトリのクローン、コミットのプッシュ、ブランチの管理、プルリクエストの作成およびレビュー、マージコンフリクトへの対処、およびIssueの変更に関するディスカッションが可能です。 あなたも学生も、リポジトリのコミット履歴をレビューできます。 For more information, see "[Getting started with {% data variables.product.prodname_dotcom %}](/github/getting-started-with-github)," "[Repositories](/repositories)," and "[Collaborating with issues and pull requests](/github/collaborating-with-issues-and-pull-requests)."

- 課題を完了した学生がいる場合には、その学生のリポジトリにあるファイルをレビューできます。また、学生の作業についてをより深く理解するため、リポジトリの履歴や視覚化されたデータを確認できます。 詳しい情報については、「[リポジトリデータをグラフで可視化する](/github/visualizing-repository-data-with-graphs)」を参照してください。

- プルリクエストの内の個々のコミットや行にコメントすることで、課題にフィードバックを行うことができます。 詳しい情報については、「[プルリクエストへコメントする](/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/commenting-on-a-pull-request)」および「[コードから Issue を開く](/github/managing-your-work-on-github/opening-an-issue-from-code)」を参照してください。 一般的なエラーに対するフィードバックを行うための、返信テンプレートの作成に関する詳しい情報については、「[返信テンプレートについて](/github/writing-on-github/about-saved-replies)」を参照してください。

## 参考リンク

- "[{% data variables.product.prodname_global_campus %} for teachers](/education/explore-the-benefits-of-teaching-and-learning-with-github-education/github-global-campus-for-teachers)"
- 「[学習管理システムを{% data variables.product.prodname_classroom %}に接続する](/education/manage-coursework-with-github-classroom/connect-a-learning-management-system-to-github-classroom)」
