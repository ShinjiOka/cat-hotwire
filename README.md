参考記事
・https://zenn.dev/shita1112/books/cat-hotwire-turbo/viewer/tutorial-1

empty?
・https://nishinatoshiharu.com/rails-boolean-methods/

ransack、name_cont
・https://pikawaka.com/rails/ransack
・https://qiita.com/gyu_outputs/items/6cad794b4ca3868e976e

helper
・https://www.sejuku.net/blog/28563

redirect_to
・https://www.sejuku.net/blog/27603
・https://qiita.com/Kohei_Kishimoto0214/items/65a771cacc43322f2312

link_to
・https://www.javadrive.jp/ruby/if/index11.html

エラーメッセージ取得
・https://qiita.com/ATORA1992/items/218f17deb66c82f27fbc

bootstrapのよく使うクラス
・https://qiita.com/nakanishi03/items/c80a16b9b9796c25f890
・https://bootstrap-guide.com/utilities/spacing

%w
・https://magazine.techacademy.jp/magazine/18702

current_page
・https://shonoooo.hatenablog.com/entry/2017/10/31/232302
・https://qiita.com/takehanKosuke/items/f4f2e49e84576a555ee6
current_page?(path)
というメソッドを使っており、これは引き数のpathと現在いるpathが等しければtrueを返しそうでなければfalseを返してくれるものです。

if文を一行で書くやり方
・https://magazine.techacademy.jp/magazine/30875
・https://www.javadrive.jp/ruby/if/index11.html

<<
・https://qiita.com/mnuma/items/22338399a86064c61f24

class="active"
・https://jp.linkedin.com/learning/designing-a-responsive-website-with-bootstrap/523872
・https://stackoverflow.com/questions/39153464/set-class-active-using-current-page-for-index-and-show-actions

content_tag
・https://qiita.com/onikan/items/6a2df551c18f39bacf76

iタグ
・https://html-coding.co.jp/annex/dictionary/html/i/

class: bi
・https://icons.getbootstrap.com/icons/person-fill/

alert
・https://getbootstrap.jp/docs/5.0/components/alerts/

paginate
・https://qiita.com/no_threehouse/items/313824b90a31268b0074

kaminari
・https://nekorails.hatenablog.com/entry/2018/10/15/005146

form_withのmodel指定について
・https://qiita.com/kajikaji/items/5b5687fbb8ad287560fc

dom_id
・https://blog.piyo.tech/posts/2014-09-01-200000/

RailsでモデルのインスタンスからURLのパスを取得する仕組み
・https://zenn.dev/pofkuma/articles/7eaaf9cbc60c42

link_to_unless
・https://hai3.net/blog/rails-link_to-helper-family/

raw
・https://shinkufencer.hateblo.jp/entry/2020/09/26/231037

remote
・https://song-of-life.hatenablog.com/entry/2017/09/30/234356

ajax
・https://qiita.com/hisamura333/items/e3ea6ae549eb09b7efb9

=============================================================

わからない部分
    ・application_helper.rb
        ・classesのとこ x
        ・if current_page(path)のとこ x
        ・active △ (色の指定場所は?)
        ・tag.spanのとこ x
        ・tag.iのとこ x
        ・module x
    
    ・_flash.html.erb
        ・classが適用されているところ全部 x

    ・_sidebar.html.erb
        ・classが適用されているところ x
        ・sidebar_link_toのところ x

    ・_cat.html.erb
        ・classが適用されているところ x

    ・cats/edit.html.erb
        ・@catについて調べておく △
        ・https://26gram.com/ruby-variables ← ＠catの解決記事

    ・cats_controller.rb
        ・@search.resultのとこ x

    ・cats/index.html.erb
        ・icon_with_textのとこ x
        ・search_form_forのとこ x
        ・sort_linkのとこ x
        ・paginateのとこ x

    ・cats/new.html.erb
        ・@catのとこ x

    ・cats/show.html.erb
        ・dom_idのとこ x
        ・button_toに@catを渡している部分を調べておく x

    ・_first_page.html.erb
        ・link_to_unlessのとこ x
        ・current_page.first?のとこ x
        ・rawのとこ △
        ・url, remoteのとこ △

    ・_gap.html.erb
        ・link_to rawのとこ △

    ・_last.html.erb
        ・link_to_unless current_page.last?のとこ x

    ・_page.html.erb
        ・content_tagのとこ x
        ・relのとこ △

    ・_paginator.html.erb
        ・first_page_tag、prev_page_tag、next_page_tag、last_page_tagのとこ x
        ・current_page.first?、current_page.last?のとこ x

    ・rotes.rb
        ・redirect("/cats")の書き方のとこ x