1. 透過[chatGPT](https://chat.openai.com/auth/login)產生文本故事

2. 將產生的文本故事斷句，透過[Midjourney](https://midjourney.com/home/?callbackUrl=%2Fapp%2F)請AI幫我們作畫(設定seed數值可使風格一樣，圖片連貫)

3. 透過python pyttsx3 文本轉語音

4. 判斷語音長度，來控制照片持續的秒數(pydub-AudioSegment)

5. 使用moviepy來合成圖片序列、語音檔