## Mobile Application Testing
During my training course, I worked with [Shopping List](https://drive.google.com/file/d/1wSz1J4Ba-VDgjv82RIk59EaQ1Ys16ph8/view?usp=share_link) Android app. The testing was conducted using Google Pixel 9 emulator in Android Studio. Here you can review some of the test artifacts I created: 

(NOTE: the artifacts are available only in Russian)
- [Checklist](https://docs.google.com/spreadsheets/d/1qrYEyXL0olEO4zsIEYPECWNsSej22lO2xgqQeJ-UGN4/edit?usp=sharing)
- [Test cases via Qase (pdf)](https://github.com/imurashev/mobile/blob/main/Test%20cases%20for%20'shopping-list'%20mobile%20app.pdf)
- [Test run results via Qase (pdf)](https://github.com/imurashev/mobile/blob/main/%D0%A2%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D1%8B%D0%B9%20%D0%BF%D1%80%D0%BE%D0%B3%D0%BE%D0%BD%20-%20shopping-list.pdf)
- [Bug Reports via YouTrack (xlsx)](https://github.com/imurashev/mobile/blob/main/%D0%9E%D1%82%D1%87%D0%B5%D1%82%20%D0%BE%20%D0%B4%D0%B5%D1%84%D0%B5%D0%BA%D1%82%D0%B0%D1%85%20-%20shopping-list.xlsx)
- [Test summary report (pdf)](https://github.com/imurashev/mobile/blob/main/%D0%9E%D1%82%D1%87%D0%B5%D1%82%20%D0%BE%20%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D0%B0%D1%85%20%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20shopping-list.pdf)

Using Charles Proxy, I also performed several tasks involving traffic interception and modification on [demoshopping.ru](https://demoshopping.ru/):

(check out [the video](https://drive.google.com/file/d/12JUp94OQ3aukj8ZIEbW3Z-dFPWOcvF9M/view?usp=sharing) to see my solutions)

- Modification of the request to remove one item from the cart, which actually removes a completely different item
- Simulating a scenario where a user sees any image in the browser when accessing the website
- Display any intercepted HTTPS request from a mobile device where the User-Agent header contains information about that mobile device
