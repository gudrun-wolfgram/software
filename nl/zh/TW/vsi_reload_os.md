---



copyright:
  years: 2017
lastupdated: "2017-09-25"


---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}

#  重新載入 OS
您隨時可以在裝置上重新載入作業系統 (OS)，以將裝置還原至其原始工作單，或使用不同的軟體來重新配置裝置。OS 重新載入會移除裝置中的所有資料，並套用「類似新版」配置（如「OS 重新載入」設定的配置處理程序期間所指定）。因為 OS 重新載入會清除裝置中的所有資料，所以如果未在重新載入之前備份資料，則會將它永久地刪除，而無法予以擷取。
{:shortdesc}

**重要事項：**如果您要保留資料，請在執行 OS 重新載入之前備份所有資料。

## 重新載入 OS
1. 從**裝置清單**中，按一下需要「OS 重新載入」的伺服器，以顯示「裝置詳細資料」頁面。
2. 從**動作**功能表中，選取 **OS 重新載入**。
3. 決定您是要重新載入現有配置，還是使用新的配置來重新載入裝置。

   <table>
   <CAPTION>表 1. OS 重新載入選項</CAPTION>
   <THEAD>
   <TR>
   <th>重新載入類型</th>
   <th>步驟</th>
   </TR>
   </THEAD>
   <TBODY>
   <tr>
   <td>如果您要重新載入新的配置...</td>
   <td>
   <ol>
   <li>針對需要更新的「種類」，按一下<b>編輯</b>。</li>
   <li>從<i>選取軟體</i> 下拉清單中，選取要套用至裝置的新軟體。</li>
   </ol>
   </td>
   </tr>
   <tr>
   <td>如果您要重新載入現有配置...</td>
   <td>請繼續進行下一步。</td>
   </tr>
   </TBODY>
   </table>

4. 判斷是否要在佈建裝置之後套用後置安裝 Script。

   如果您要套用後置安裝 Script，請從「現有 Script」下拉清單中選取該 Script，或輸入新 Script 的完整 URL。否則，請繼續進行下一個步驟。

5. 針對實體裝置，判斷是要新增還是移除已安裝的分割區，或是應該將它們保持不變。
   
   <table>
   <CAPTION>表 2. 分割區動作選項</CAPTION>
   <THEAD>
   <TR>
   <th>分割區動作</th>
   <th>步驟</th>
   </TR>
   </THEAD>
   <TBODY>
   <tr>
   <td>若要新增已安裝的分割區...</td>
   <td>
   <ul>
   <li>按一下<b>新增另一個分割區</b>鏈結。</li>
   <li>輸入分割區的確切名稱。</li>
   <li>輸入分割區大小 (GB)。如果您要的話，可以選取「成長」讓分割區成長，以填入其餘的磁碟空間。
   <p><b>附註：</b>一次只能選取一個分割區，讓其成長。此分割區會大於指定的大小，並填入所有可用的容量。「成長」分割區容量的計算方式是將「已安裝的分割區」區段中所提供的「總容量」數目減去所有其他分割區的結合大小。</p>
   </li>
   </ul>
   </td>
   </tr>
   <tr>
   <td>若要刪除已安裝的分割區...</td>
   <td>按一下<b>刪除</b>，以刪除分割區。</td>
   </tr>
   <tr>
   <td>若要保持不變...</td>
   <td>請繼續進行下一步。</td>
   </tr>
   </TBODY>
   </table>
    
6. 判斷是否將一個以上的「SSH 金鑰」套用至裝置。

7. 針對您要在 OS 重新載入期間或之後套用至裝置的選項，選取適用的勾選框。

   **附註：**選項會根據裝置而不同。並非每個裝置都能使用所有選項。

8. 按一下**重新載入上方配置**，以繼續進行檢閱。按一下**取消**，以取消裝置變更並結束畫面。

9. 驗證「新建配置」區段中的所有詳細資料都正確。  

10. 按一下**確認 OS 重新載入**，以確認並起始「OS 重新載入」。按一下**取消**即可取消動作。

## 下一步為何？
在起始 OS 重新載入處理程序之後，裝置會離線，並開始「OS 重新載入」處理程序。
執行 OS 重新載入所需的時間會隨著裝置的現行配置及新配置而不同。
在整個配置處理程序期間，會將「OS 重新載入」的最短時間顯示在每一個畫面上。
所顯示的時間範圍是系統所產生的預估值。如果重新載入費時超過 24 小時，請與「IBM 支援中心」聯絡。

裝置重新上線時，會如「OS 重新載入」的新配置中所指定一樣地運作。所有先前儲存至裝置的資料都會遺失，但可以在 OS 重新載入之前建立裝置備份時進行還原。如果資料未備份，就無法進行擷取。
 
您需要向 eVault 重新登錄裝置。<!--using the folliwng link: ![External link icon](../icons/launch-glyph.svg "External link icon")](https://knowledgelayer.softlayer.com/procedure/how-do-i-re-register-evault){: new_window}.-->
