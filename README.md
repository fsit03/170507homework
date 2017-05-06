# 《前情提要》


好密碼的條件：愈長、愈亂、愈與個人資料無關。問題是，這樣子的密碼會不會就愈記不住？

於是，某人就想啦－－既然記不住，不如就將密碼寫下來，例如，銀行密碼就寫在提款卡的背面，但是，最重要的就是但是：不要寫得太直白。

怎麼辦呢？他參考 http://ppt.cc/rELO 寫了一支亂數產生器，程式請參考 index.html

程式寫出來後，輸入1234並且產生亂數表。如下：

01: 3499305845 <br>
02: 1769646932 <br>
03: 3175789704 <br>
04: 4592818053 <br>
05: 1597861333 <br>
06: 4414077977 <br>
07: 2122376182 <br>
08: 1169150223 <br>
09: 6149827002 <br>
10: 1990694015 <br>


接下來，在提款卡背面寫下:

13 31 62 18 32 62 73 43

他的意思是：密碼的－－
第一個字元是第一橫列，第三直欄，也就是 9； <br>
第二個字元是第三橫列，第一直欄，也就是 3； <br>
(以下類推...) <br>
銀行密碼：93481429。 <br>


好極了，以後就只需記得例如 1234 這組密碼即可。




# 《家庭作業》

試用過程式之後，請從下列方面想想看該怎麼加強：

1. 美化操作介面。
   例如套用 Bootstrap 之類的套件。

2. 加強程式功能。
   例如，讓使用者可選純數字或者「數字＋字母」，
   可自行設定行數之類的。

3. 寫作操作文件。利用 HTML 說明如何使用本程式。




# 《參考資料》
http://davidbau.com/archives/2010/01/30/random_seeds_coded_hints_and_quintillions.html

