# ilovechatgpt
首先先看一下chatgpt的效果，紅色框框是我的輸入，綠色框框是chatgpt的回應
![image](https://raw.githubusercontent.com/treeaaa/ilovechatgpt/main/img/%E4%BB%A4%E4%BA%BA%E9%A9%9A%E8%B1%94%E7%9A%84chatgpt/0.PNG)

有夠厲害的，天啊!

我不是專業的NLP從業人員，但我完全可以感受到chatgpt的淺力。可是非常遺憾的是，我的老闆也有相同的感受，"欸那個嘗試一下chatgpt跟我們公司的QA問答要怎麼結合"。從此之後，我上班就能、就要、就必須正大光明的跟chatgpt聊天。

也因為這樣頻繁的與chatgpt交互，我發現一些以前NLP很難解決的問題，現在好像容易許多，譬如說"會議結論"這件事情，沒有chatgpt的時候不知道怎麼做特徵工程，有了chatgpt之後就是要多少字的都沒問題，反正也不是我寫，哈哈。

另外我在survey老闆交付任務的時候，發現chatgpt for NLP task，這方面的資源不多，所以沒辦法站在巨人的肩膀上，可惜了。沒有巨人，很多事情就只能自己探索，我們已經在這條路上走了一段時間了。如果不幸你的老闆，也有感受到chatgpt的淺力，想做一些chatgpt & nlp的嘗試，也許你可以從我的文章中得到一些啟發，更快速地完成工作。

如果要選一個使用chatgpt的重點，我認為應該是"引導"，引導chatgpt回答出我們想要的答案,型式,...，之後我會整理一下比較有意思的東西，並且分享出來，我自己把它叫做"prompt block"。今天先介紹一個我覺得很重要的prompt block，"YN_block"，這個block的用途是

如何不讓chatgpt胡說八道?

首先看一下範例

![image](https://raw.githubusercontent.com/treeaaa/ilovechatgpt/main/img/%E8%83%A1%E8%AA%AA%E5%85%AB%E9%81%93/0.PNG)

這個文本裡面有兩條我們公司的QA，但很明顯的並不包含公司八樓飲水機的訊息。那再看看chatgpt的回答，好像也還可以，中規中矩。但是這樣有一個問題，，搞不好我們公司根本沒有大廳櫃台，或是整間公司就我一個人，或是我們公司根本沒有飲水機，答案可能不是準確的。那為了解決chatgpt的回答可能不準確的問題，所以我希望他只能夠按照文本來回答，如果回答不出來的，就不要回答了，直接轉接人工客服就好，那要怎麼做到這件事情呢?

聰明的你可能已經意識到，這可能可以轉換成為一個異常檢測的問題，但讓我展示一下chatgpt的方法
![image](https://raw.githubusercontent.com/treeaaa/ilovechatgpt/main/img/%E8%83%A1%E8%AA%AA%E5%85%AB%E9%81%93/1.PNG)

透過這樣子的方式，就可以區分出能回答&不能回答的區別了，我甚至請chatgpt再開頭加上字母Y&N，方便讓我做後處理。看到這裡，可能漸漸地能體會到"引導"的重要性。之後我會不定期的再分享一些我的使用心得出來，

發這篇文張最主要的目的是找同好，如果想要討論/詢問/分享chatgpt for NLP，那就太棒了

github https://github.com/treeaaa/ilovechatgpt\
mail hot96307@gmail.com\
fb私訊 

都是可以聯繫到我的方式，那今天就到這邊告一段落，謝謝大家。