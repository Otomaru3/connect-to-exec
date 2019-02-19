# connect-to-exec

<h1>Components</h2>
<table>
  <tr>
    <th>Compornent</th>
    <td>Description</td>
  </tr>
  <tr>
    <th>CommList_RT.txt</th>
    <td>HostTypeがRTのホストで実行されるコマンドを定義する</td>
  </tr>
  <tr>
    <th>Connect2Exec.ttl</th>
    <td>マクロ本体。HostList.txtのホストにTelnetしコマンドを実行する。</td>
  </tr>
  <tr>
    <th>teraterm.ini</th>
    <td>Teratermの設定ファイル。好きなものに置き換えてよい。<br>
         ただし、TCP/IP設定の「自動的にウインドウを閉じる」が有効になっている必要がある。</td>
  </tr>
  <tr>
    <th>HostList.csv</th>
    <td>ホストのリスト</td>
  </tr>
</table>

<h1>Getting Started</h2>
<ol>
  <li>ダウンロード、展開</li>
  <li>Connect2Exec.ttlの文字コードをSJISで保存しなおす。</li>
  <li>HostList.txt、CommList_RT.txtを適宜編集。<br>
      HostList.txt の2列目”HostType”は"CommList_<span style="color:red;">RT</span>.txt"の"RT"に対応しています。<br>
      HostList.txtでHostTypeをL3SWと指定した場合はCommList_L3SW.txtの中身が実行されます。</li>
  <li>Connect2Exec.ttxをttpmacro.exeから実行する</li>
</ol>

 
