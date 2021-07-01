# Script list for "Redmine View Customize Plugin"

* [プロジェクト毎にヘッダの色を変える](./change_header_color_by_project.css)
* [チケット一覧を識別しやすいように装飾](./decorate_issue_list.css)
* [チケット作成時にトラッカーに応じてデフォルト値を設定](./set_default_value_at_change_tracker.js)
* [サイドバーを開閉式に](./toggle_sidebar.js)
* [「全てのチケット一覧」リンクをヘッダに](./add_issues_link_on_header.js)
* [進行中にもかかわらず担当者が未設定の場合に警告を表示](./show_alert_if_not_assign.js)
* [チケット作成、編集時の項目名を変える](./change_issue_form_filed_name.js)
* [ユーザ選択のカスタムフィールドで自分を選択する項目を先頭に追加](./add_me_for_custome_users_field.js)
* [プロジェクト一覧からの各プロジェクトへのリンク先を変更](./change_project_link_on_project_list.js)
* [カスタムフィールドを連動させる(親の値に応じて、子を絞り込む)](./link_custom_field.js)
* [コンテキストメニューを選択しやすくする](./adjust_context_submenu.css)
* [チケット一覧のコンテキストメニューでステータス変更を無効に](./handling_issue_list_context_menu.js)
* [チケットのステータスに応じて、カスタムフィールドの表示/非表示を切り替える](./change_custom_field_visibility_when_change_status.js)
* [新しいチケットタブを表示する(Redmine3.3で"+"ボタンと両立した時)](./add_new_issue_tab.js)
* [チケット一覧の進捗率にて値も表示する](./add_value_of_progress_on_issues_list.js)
* [カスタムフィールドのチェックボックスを2列で表示](./multi_column_checkbox.css)
* [チケット一覧のコンテキストメニューにコマンド追加](./add_command_to_issues_context_menu.js)
* [ステータスに応じて、カスタムフィールドの表示を切り替える](./change_custom_field_visibility_when_change_status.js)
* [チェックボックスを横並びにする](./row_checkbox.css)
* [チケット一覧のコンテキストメニューからステータスを切り替えた際に、バージョンも変更する](./change_version_when_change_status_on_context_menu.js)
* [カスタムフィールドを説明の後ろに移動](./move_custom_filed_after_description.js)
* [チケットの説明を非表示に](./hide_issue_description.js)
* [リポジトリタブでのデフォルトブランチを変更](./change_default_branch_on_repository_tab.js)
* [カスタムフィールドの値でチケット一覧のフォントをBoldに変える](./change_font_weight_by_custom_field_on_issue_list.js)
* [子チケット一覧に親子関係を外すボタンを追加し、ボタン押下時にREST APIを使って親チケットの情報をクリアする](./add_button_use_rest_api.js)
* [チケット作成、編集画面の作成/送信ボタンにaccesskeyを追加する](./add_accesskey_on_issue_submit_button.js)
* [長いテキストを幅広く表示する](./display_long_text_wide.js)
* [担当者を入力補完を利用して選択する](./autocomplete_assigned_to.js)
* [REST APIを利用して複数の子チケットをまとめて作成する(バージョン1.2.0以上)](./create_children_issues_using_rest_api.js)
* [REST APIを利用して複数の関連チケットをまとめて作成する(バージョン1.2.0以上)](./create_relation_issues_using_rest_api.js)
* [REST APIを利用して親チケットの情報をクリアする(バージョン1.2.0以上)](./delete_parentage_relationship_using_rest_api.js)
* [子チケット作成時に親チケットの情報を引き継ぐ(バージョン1.2.0以上)](./take_over_information_when_adding_child_issue.js)
* [クリップボードから画像を貼り付ける(バージョン1.2.0以上)](./copy_image_from_clipboard.js)
* [テキストエリアで入力補完(バージョン2.1.0以上)](./input_suggestion_on_textarea.html)
* [プロジェクトを変更したら、強制的に担当者を変更する(バージョン1.2.0以上)](./change_assignee_when_change_project.js)
* [カスタムフィールドの入力欄をトラッカーの後ろに移動(バージョン1.2.0以上)](./move_custom_filed_input_after_tracker.js)
* [ステータスを却下にしたときに、期日が未入力だったら今日の日付を入れる(バージョン1.2.0以上)](./set_today_to_due_date_when_resolved.js)
* [プロジェクトを変更したら、ウォッチャーを変更する(バージョン1.2.0以上)](./change_watcher_when_change_project.js)
* [特定のプロジェクトでファイル添付を非表示にする](./hide_attachments_form.css)
* [カスタムフィールドを3カラムで表示する(バージョン1.2.0以上)](./change_3column_custom_fields.js)
* [親のカスタムフィールドが選択されたら、子のカスタムフィールドも入力可能に(バージョン1.2.0以上)](./enable_when_custom_field_selected.js)
* [期日の3日前になったら警告を表示(バージョン1.2.0以上)](./show_alert_on_due_date.js)
* [チェックされたらテキストボックスを無効化(バージョン1.2.0以上)](./disable_text_depending_on_checked.js)
* [特定ユーザの削除、ロックボタンを非表示にする](./hide_lock_button_and_delete_button.css)
* [特定ユーザに対して一部管理者メニューを非表示にする](./hide_part_of_admin_menu.js)
* [特定の日以降は新規チケットのリンクを非表示に](./hide_new_issue_link_after_date.js)
* [チケット一覧横のSummaryリンクを非表示に](./hide_issue_summary_link.css)
* [親チケットが設定されたらカスタムフィールドを無効に](./disable_if_parent_issue_is_set.js)
