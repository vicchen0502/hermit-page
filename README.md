# hermit
A website which can post some posts anonymously as a page.
______
我想讓管理員可以自己選擇想要的投稿網頁樣式，所以我希望可以有好幾個不同的模版，愈多愈好。

## 一定要有的elements:
*   管理員登入的連結，類似：`<a href="/login">管理員登入 </a>`
*   粉專的名子（就是大標題），類似：`<span>黑特松山高中</span>`
*   粉專的大頭貼，類似：`<img src="img/ssshhate.jpg" alt="Facebook">`
*   副標題，類似：`<span>歡迎來黑特ㄎㄎ</span>`
*   關於，類似：`<p>整個松山高中都是我的黑特版。歡迎大家把所有的不滿通通發洩出來，但是言詞 請勿過於極端以及投稿包含嚴重辱罵、性暗示、無意義之圖文。</p>`
*   最下面再一個footer
*   一個表單，類似：`<form></form>`

以下都是包在`<form>`裡面的：
*   打文章的地方（上面要有label）：`<textarea placeholder="在此輸入..." name="post[text]" id="post_text"></textarea>`
*   選擇圖片的input（上面要有label）：`<input id="filebrow" type="file" accept="image/*" />`
*   可以給我放驗證碼的div，大小差不多跟<a href="http://www.disam.asia/#portfolio">黑特松山</a>的一樣就好
*   一個`<p>發佈即同意<a href="https://www.facebook.com/communitystandards">Facebook社群守則</a></p>`
*   投稿送出按鈕：`<input type="submit" name="commit" value="投稿" />`

_____
  我想讓管理員可以設定自己的投稿網頁，所以像是粉專的名子、副標題、關於等都要設計成就算是很長的字串也不會很醜。
   
  Moreover,幫我加一些管理員可以設定的的東西，像是兩個關於等等，發揮你的創意，但是不能是圖片因為我沒地方給他們上傳。

  還有就是可以的話加個navbar。

# 最後，一定要有RWD。
謝啦！
