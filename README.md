# これなに
VRMをNeosVRでインポートしやすいように変換するツールです。  
Blenderに VRM_Addon_for_Blender を自動で導入し、いい感じに値を調整しGLBで出力します。


#前提ツール
Blenderだけ入れてればOK。  
Blenderはversion3.0以降でのみ動作します(厳密には2.93 LTSまで動作確認していますが、今から導入する場合は3系をお勧めします)  
もしまだ入れていない方はこちらからどうぞ: https://www.blender.org/download/release/Blender3.2/blender-3.2.2-windows-x64.msi/

# ダウンロード
1. [ここのリンク](https://github.com/kazu0617/vrmtoglb_autoconvert/releases/latest)をクリックする
2. Source Code(zip) をダウンロードする

# 使い方
1. Blenderをインストールする
2. _convert.batにvrmファイルをD&Dする -> vrmファイルがある場所を確認して、正常に変換できている場合はglbとテクスチャのフォルダが出力される
3. glbが出ない場合は_license-check.batにvrmファイルをD&Dする
4. license-check後、出来る人は_convert_manual.batでvrmをD&D後、[N]キー -> VRM -> VRM ** Meta -> インポート時に怒られた問題を修正 -> 修正後 ファイル -> エクスポート -> VRM


# 備考
- Neosのインポート時の単位(「自動スケール」とかのやつ)は「メートル(m)」
- ライセンスチェックで引っかかったアバターは本当に入れて大丈夫か目視で確認する必要があるのでスクリプトでは動きません
- 複数ファイルも動きます。まとめてD&Dしてください
- エラーチェックは随時行っています。GitHubのIssueに直接書いてもらうか、下の二人まで

# 連絡先(Pythonスクリプト)
- Twitter: @lill_azk  
- Neos: lill

# 改変連絡先(Batchスクリプト)
- Twitter: @Gameofthebest
- Neos: kazu

# ライセンスについて
一応MITで。そのうちMPLにするかも。
