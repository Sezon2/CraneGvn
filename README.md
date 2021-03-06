# CraneGvn
SvnとGitを混合利用するためのツール開発と模索をする為のプロジェクト  
  
## ★ソフトウェア名称の由来
本ソフトウェアの正式名称は「CraneGitversion」であり、  
その名はGitとSubversionの融合体です。  
また、Craneとは機械ではなく、鳥の「鶴」を意味し、  
それは日本製のツールであることを象徴しています。  
  
尚、本ソフトウェアの読み方は「CraneGvn(クレーン・ジーブイエヌ)」です。  
  
## ★プロジェクトの方針
本プロジェクトはSvnとGitを意識することなく、同じように扱えるようにするツールの作成と普及を目標としています。  
この目標の達成に向けて、実装方法の模索とツールの作成およびパッケージのリリースを主に行ないます。  
また、普及に向けて本プロジェクトで作成するソフトウェアは無償で提供(寄付歓迎)するようにします。  
  
### ■ソフトウェアの開発方針
本プロジェクトで作成するソフトウェアは以下の方針に従う物とします。  
- 各種インターフェースはSvnを基本とするようにします。
- 開発時はできる限り「CUI版」→「CUI+版」→「GUI版」の順に実装を進めます。※１

※１：これはCUIから作り始めることで各箇所を集中的に開発する事が出来、  
　　　結果として、品質のよいソフトウェアを作成することができる為です。  

----------------

## ★ブランチ一覧
| ブランチ名      | 説明                                                        |
|:---------------:|:------------------------------------------------------------|
| master          | パッケージ置き場                                            |
| branch_template | 空のブランチ新規作成用テンプレート                          |
| WinCUI          | Windows用のCUIアプリケーション開発用                        |
| WinCUI+         | Windows用のCUI+GUI(CUIベース)アプリケーション開発用【予定】 |
| WinGUI          | Windows用のGUIアプリケーション開発用【予定】                |
