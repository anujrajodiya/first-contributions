# प्रथम योगदान

<img align="right" width="300" src="../assets/fork.png" alt="fork this repository" />

पहली बार कुछ करना कठिन होता है| ख़ास तौर पर जब आप मिलकर काम कर रहे हों तब गलतियां करना एक अच्छी बात नहीं है| मगर आपस में मिलना और एक जुट होकर काम करना ही तो है ओपन सोर्स| हम आपका ये पहला ओपन सोर्स कॉन्ट्रिब्यूशन आसान बनाने में आपकी मदद करेंगे|

आर्टिकल्स पढ़ना और ऑनलाइन ट्यूटोरियलज़ देखना मदद कर सकते हैं मगर बिना कुछ गलत करे खुद वो काम करने से अच्छा क्या हो सकता है? यह प्रोजेक्ट आपको आपके पहले कॉन्ट्रिब्यूशन के लिए दिशा निर्देशन में मदद करेगा| याद रखिये - जितने तनाव मुक्त होकर आप सीखेंगे उतना ही बेहतर सीख पाएंगे| अगर आप अपनी पहली कॉन्ट्रिब्यूशन करना चाहते हैं तो आगे दिए गए स्टेप्स को फॉलो करें|

अगर आपके मशीन पर Git नहीं है तो, [इसे स्थापित करें](https://help.github.com/articles/set-up-git/)

## रिपॉज़िटरी को फॉर्क करना

कांटा बटन पर क्लिक करके इस रिपॉज़िटरी को फॉर्क कर सकते हैं| यह आपके खाते में इस रिपॉज़िटरी की एक प्रति (कॉपी) बना देगा।

## रिपोजिटरी क्लोन

<img align="right" width="300" src="../assets/clone.png" alt="clone this repository" />

अब आप यह रेपो अपने मशीन में क्लोन करें| अपने गिटहब खाते पर जाएं, क्लोन बटन पर क्लिक करें और फिर कॉपी टू क्लिपबोर्ड आइकॉन पर क्लिक करें|

एक टर्मिनल खोलें और निम्न git आदेश चलाएँ:

```
git clone "यूआरएल जिसे आपने अभी कॉपी किया"
```

जहाँ े "यूआरएल जिसे आपने अभी कॉपी किया" (उद्धरण चिह्नों के बिना) इस भंडार के लिए यूआरएल है।(इस परियोजना का आपका फॉर्क) यूआरएल प्राप्त करने के लिए पिछले चरण देखें।

उदाहरण के लिए:

```
git clone https://github.com/यह-तुम-हो/first-contributions.git
```

<img align="right" width="300" src="../assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

`यह-तुम-हो` आपके GitHub अकाउंट का नाम है। यहाँ आप अपने कंप्यूटर में GitHub से फर्स्ट-कंट्रिब्यूशंज़ रेपो को आप कॉपी कर रहे हैं|

## एक ब्राँच बनाएं

अपने कंप्यूटर पर रिपोजिटरी डायरेक्टरी में बदलें (अगर अभी तक नहीं की है तो)

```
cd first-contributions
```

अब एक शाखा बनाएं `git checkout command` उपयोग करके|

```
git checkout -b <अपनी-शाखा-का-नाम-जोड़ें>
```

उदाहरण के लिए:

```
git checkout -b add-alonzo-church
```

(शाखा के नाम में `add` जोड़ने की आवश्यकता नहीं है, लेकिन इसमें शामिल होना उचित बात है क्योंकि इस शाखा का उद्देश्य एक सूची में अपना नाम जोड़ना है।)

## आवश्यक परिवर्तन करें और उन परिवर्तनों को कमिट करें-

अब `Contributors.md` फ़ाइल को एक टेक्स्ट एडिटर में खोलकर इसमें अपना नाम लिखें। फ़ाइल की शुरुआत या अंत में इसे न जोड़ें। इसे बीच में कहीं भी रखें| 

<img align="right" width="450" src="../assets/git-status.png" alt="git status" />


आप अगर `git status` निर्देश चलाएंगे , तो आप परिवर्तन देखेंगे।

उन परिवर्तनों को नीचे `git add` कमान्ड का उपयोग कर जोड़ें।

```
git add Contributors.md
```

अब अपने किये गए बदलावों को कमिट करें `git commit` आदेश का उपयोग करके|

```
git commit -m "Add <आपका-नाम> to Contributors list"
```

<आपका-नाम> की जगह अपना नाम डालें|

## अपने बदलावों को github में पुश करें|

`git push` का उपयोग कर अपने परिवर्तन को पुश करें|

```
git push origin <अपनी-शाखा-का-नाम-जोड़ें>
```

`<अपनी-शाखा-का-नाम-जोड़ें>` की जगह अपनी शाखा का नाम डालें|

## अपने बदलावों को रिव्यु के लिए सबमिट करें|

अगर आप अपने github प्रोफाइल पर अपनी रेपो में जायेंगे तो आपको Compare & pull request का ऑप्शन दिखेगा| उसे दबाएं|
<img style="float: right;" src="../assets/compare-and-pull.png" alt="create a pull request" />

अब अपनी pull request सबमिट करें|

<img style="float: right;" src="../assets/submit-pull.png" alt="submit pull request" />
जल्द ही मैं आपके बदलावों को इस प्रोजेक्ट की मास्टर शाखा में मर्ज क्र दूंगा| आपको एक मेल आजायेगी जब आपके बदलाव मर्ज होंगे|

## पुल अनुरोध मर्ज के बाद शाखा हटाएं

पुल अनुरोध मर्ज होने के बाद आप अपनी शाखा को सुरक्षित रूप से हटा सकते हैं। शाखा को हटाने के लिए आपको एक बटन दिखाई देगा:

<img style="float: right;" src="../assets/delete-branch-after-pr.png" alt="delete branch after PR is merged" />

अगर पुल अनुरोध मर्ज किए बिना बंद कर दिया गया था, तो github आपको मर्ज न किए गए कामों को हटाने के बारे में चेतावनी देगा और बटन इस तरह दिखेगा:

<img style="float: right;" src="../assets/delete-branch-warning.png" alt="delete branch after PR is not merged" />

## यहाँ से कहाँ जाएं ?

बधाई! आपने अभी पूरा कर लिया है _fork -> clone -> edit -> PR_ वर्कफ़्लो जो आप अक्सर योगदानकर्ता के रूप में सामना करेंगे!

अपने पहले योगदान की खुशी में जश्न मनाएं और अपने दोस्तों के साथ शेयर करें [वेब एप्प](https://roshanjossey.github.io/first-contributions/#social-share) पे जाके| 

आप हमारी स्लैक टीम को ज्वाइन कर सकते हैं अगर आपको कोई मदद चाहिए या आपके कोई परेशानी हों| [स्लैक पे ज्वाइन करें](https://firstcontributions.herokuapp.com)

अब आप और प्रोजेक्ट्स में कंट्रीब्यूट करना शुरू कर सकते हैं| हमने आपके लिए एक लिस्ट बनायीं है जो कि बहुत आसान मुद्दे हैं| [प्रोजेक्ट्स कि लिस्ट](https://roshanjossey.github.io/first-contributions/#project-list)

## अन्य टूल का उपयोग करके ट्यूटोरियल

|<a href="../github-desktop-tutorial.md"><img alt="GitHub Desktop" src="https://desktop.github.com/images/desktop-icon.svg" width="100"></a>|<a href="../github-windows-vs2017-tutorial.md"><img alt="Visual Studio 2017" src="https://www.visualstudio.com/wp-content/uploads/2017/11/microsoft-visual-studio.svg" width="100"></a>|<a href="../gitkraken-tutorial.md"><img alt="GitKraken" src="../assets/gk-icon.png" width="100"></a>|
|---|---|---|
|[GitHub Desktop](../github-desktop-tutorial.md)|[Visual Studio 2017](../github-windows-vs2017-tutorial.md)|[GitKraken](../gitkraken-tutorial.md)|

## आत्म पदोन्नति

अगर आपको यह प्रोजेक्ट पसंद आया, तो इसे स्टार करें [GitHub](https://github.com/Roshanjossey/first-contributions) पर| 
यदि आप विशेष रूप से धर्मार्थ महसूस कर रहे हैं, तो follow [Roshan](https://roshanjossey.github.io/) twitter और
[GitHub](https://github.com/roshanjossey) पर|

<a href="http://saasgrids.com"> <img alt="https://app.saasgrids.com" src="../assets/saasgrids-banner.png" width="500"></a>