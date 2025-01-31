# প্রভাত

প্রভাত (Probhat) কীবোর্ড লেআউট একটি ফ্রি, ইউনিকোড-ভিত্তিক, নির্দিষ্ট বিন্যাসের বাংলা টাইপিং ব্যবস্থা, যা সাধারণত লিনাক্স ডিস্ট্রিবিউশনে পাওয়া যায়।

|CMD|ALT|CTRL|
|:---:|:---:|:---:|
|⌘|⌥|⌃|

অর্থাৎ, `Probhat` লেআউট সক্রিয় থাকলেও, আপনি এখনো `⌘+A` দিয়ে সব নির্বাচন করতে পারবেন, `⌘+C` দিয়ে কপি করতে পারবেন, `⌃+D` দিয়ে EOF পাঠাতে পারবেন বা অন্যান্য `⌘+⌥` সংমিশ্রণ ব্যবহার করতে পারবেন।

## লেআউট

![প্রভাত লেআউট](https://bn.wikipedia.org/wiki/%E0%A6%9F%E0%A7%87%E0%A6%AE%E0%A6%AA%E0%A7%8D%E0%A6%B2%E0%A7%87%E0%A6%9F:%E0%A6%AA%E0%A7%8D%E0%A6%B0%E0%A6%AD%E0%A6%BE%E0%A6%A4_%E0%A6%95%E0%A7%80%E0%A6%AC%E0%A7%8B%E0%A6%B0%E0%A7%8D%E0%A6%A1_%E0%A6%B2%E0%A7%87%E0%A6%86%E0%A6%89%E0%A6%9F)

## ইনস্টল (macOS Sequoia 15 পর্যন্ত পরীক্ষিত)

টার্মিনালে নিচের কমান্ডটি চালান।

```bash
curl https://raw.githubusercontent.com/anisafifi/probhat-keyboard-macos/main/install.sh | sudo bash
```

এরপর, আপনার পাসওয়ার্ড প্রবেশ করান যাতে ইনস্টলার স্ক্রিপ্ট প্রয়োজনীয় ফাইলগুলো `/Library/Keyboard\ Layouts` ডিরেক্টরিতে কপি করতে পারে।

## আনইনস্টল

টার্মিনালে নিচের কমান্ডটি চালান।

```bash
curl https://raw.githubusercontent.com/anisafifi/probhat-keyboard-macos/main/uninstall.sh | sudo bash
```

এরপর পরিবর্তন কার্যকর করতে কম্পিউটার রিবুট করুন অথবা লগআউট করুন।

## কনফিগার

1. ইনস্টল করার পর রিবুট করুন অথবা পুনরায় লগ ইন করুন।
2. `System Preferences` খুলুন, তারপর যান `Language & Region` > `Keyboard Preferences` > `Input Sources`।
3. `+` আইকনে ক্লিক করুন, তারপর `Others` > `Probhat` (বাংলাদেশি পতাকার আইকন সহ) নির্বাচন করুন।
4. তারপর `Keyboard Preferences` > `Shortcuts` > `Input Sources` এ যান এবং `Select the previous input source` অপশন চালু করুন ও শর্টকাট কী `⌘+Space` সেট করুন।
5. এখন আপনি মেনুবারে ইনপুট মেথড তালিকায় `Probhat` দেখতে পাবেন।

    ![কিবোর্ড নির্বাচন](images/ime.png)
    
6. যেকোনো টেক্সট এডিটর, ব্রাউজার, ফেসবুক বা অন্য কোথাও যান, `⌘+Space` চাপুন এবং প্রভাত লেআউটে বাংলা টাইপ করা শুরু করুন!

    ![লেখার নমুনা](images/text.png)

## লাইসেন্স

এই কীবোর্ড লেআউটটি MIT লাইসেন্সের আওতায় উন্মুক্ত।