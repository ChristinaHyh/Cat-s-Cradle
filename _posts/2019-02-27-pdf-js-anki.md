---
layout: post
title: 'PDF.js+Chrome+Anki=Contextual Dictionary'
date: 2019-02-27
author: Christina
lang: en
tags: Tools
subtitle: Learning specialty English joyfully

---


---

### **Introduction**

Recently, I need to read lots of literature. Lacking of professional vocabulary, I have to find some tools that can assist while won't be addicted to. Focusing on solving this problem, I found a tool developed by [Zhenyu Huang](https://www.laohuang.net/20180213/online-dictionary-helper/) that can help look up words efficiently and build contextual dictionary synchronously. This post was written to introduce how to install and use this tool.

### **Tools**

* Chrome ([Link](https://www.google.com/chrome/)丨[Download](https://github.com/ChristinaHyh/ICE-9/releases/download/1.0/chrome.exe)) 
* Anki PC Version ([Link](https://apps.ankiweb.net/)丨[Download](https://github.com/ChristinaHyh/ICE-9/releases/download/1.0/anki-2.0.exe))
* Anki for Android (Download from APP store)
* Online Dictionary Helper ([Link](https://chrome.google.com/webstore/detail/online-dictionary-helper/lppjdajkacanlmpbbcdkccjkdbpllajb?hl=zh-CN)丨[Download](https://github.com/ChristinaHyh/ICE-9/releases/download/1.0/dic.crx)) 
* Anki-connect ([Link](https://github.com/FooSoft/anki-connect)丨[Download](https://github.com/ChristinaHyh/ICE-9/releases/download/1.0/ankiconnect.zip))
* PDF.js ([Link](https://mozilla.github.io/pdf.js/)丨[Download](https://github.com/ChristinaHyh/ICE-9/releases/download/1.0/pdfjs.zip))
* Anki Card Template ([Download](https://github.com/ChristinaHyh/ICE-9/releases/download/1.0/anki.apkg))

### **Installation**

**1. Installing  Chrome、Anki (Windows)、Anki (Android/iPhone)**

Considering the compatibility between Anki and AnkiConnect plug-in, I recommend installing Anki 2.0. You can download old version on the official website or download directly in this post.

**2. Installing Online Dictionary Helper (Chrome Extension)**

Click the Chrome menu icon and select Extensions from the Tools menu. Ensure that the "Developer mode" checkbox in the top right-hand corner is checked.
      
![](/assets/img/a.png)

![](/assets/img/b.png)
      
Open Google Chrome and go to the Extensions page by typing "chrome://extensions" in the address bar and pressing Enter. Drag and drop "dic.crx" onto the Extensions page.

**3. Installing Anki Connect** 

Unzip "ankiconnect.zip" and copy "AnkiConnect.py" into the plug-in folder of Anki and then restart Anki.
      
**4. Importing Anki Template**

Start Anki program, click the File menu and then "Import". Select "anki.apkg" to import the template.
      
![](/assets/img/d.png)
      
AnkiWeb is a service that allows you to keep your collection synchronized across multiple devices, and to study online. I recommend signing up for a [free account](https://ankiweb.net/) before you use it.

**5. Configuration**

Click "Details" of ODH Extension and check the option "Allow access to file URLs".

![](/assets/img/e.png)
      
Start Anki and log in your account. Click "Extension options" in ODH Extension.
      
![](/assets/img/f.png)
      
Select AnkiConnect or AnkiWeb in "Services Options", you can also change the dictionary in the "Dictionary Options".
      
The following is my configuration, you can set according to your personal preferences.
      
![](/assets/img/g.png)

![](/assets/img/h.png)

![](/assets/img/i.png)      
        
**6. Installing PDF.js**

Unzip "pdfjs.zip". Open Google Chrome by typing "/pdfjs-2.0.943-dist/web/viewer.html"in the address bar and pressing Enter.  Click the button showed as the following picture.

![](/assets/img/j.png)

**7. Using ODH to look up words and making Anki card**

Turn on ODH Extension and open any pdf file by PDF.js, move your mouse cursor over the word that you want to select and translate. Click "+" to make an Anki card. You can browser these cards across multiple devices. To get the definition, click on the blank of the card.
       
![](/assets/img/k.png)

![](/assets/img/l.png)

![](/assets/img/m.png)

Anki is a very powerful tool. If you are interested in other functions, just explore it.

---

### 2020-03-07 Updated

As of February 2020, Anki (Windows) versions lower than 2.1 are no longer able to connect to Anki Web. This guide will show you how to install AnkiConnect within the Anki 2.1 environment. It is important to note that if you are currently using Anki 2.0 and the corresponding AnkiConnect version, you may experience some compatibility issues. For more detailed instructions and information, please refer to the [Document](https://ankiweb.net/shared/info/2055492159).

Anki 2.1 | [Download Link](https://apps.ankiweb.net/) | [Download Immediately](https://github.com/ChristinaHyh/ICE-9/releases/download/1.0/anki-2.1.exe) 

Start Anki program, click "Tools" → "Add-ons" → "Get Add-ons" and then input the code of `2055492159` in the Code bar. Click "ok" to install AnkiConnect. After installation, restart Anki.

![](/assets/img/2020-03-07_193146.png)

![](/assets/img/2020-03-07_193250.png)

