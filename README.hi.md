# TelunKey
[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

TelunKey एक नटिव macOS शॉर्टकट लॉन्चर है जो ऐप सक्रियण और विंडो चयन को एक ही की-फ्लो में पूरा करता है।

- तेज़ प्रतिक्रिया, कम संसाधन-खर्च और न्यूनतम व्यवधान के लिए नटिव Swift में बनाया गया
- बाएँ/दाएँ Command (0 विलंब या कस्टम विलंब), बाएँ/दाएँ Option (0 विलंब या कस्टम विलंब) और Space ट्रिगर (दैनिक टाइपिंग को प्रभावित न करने के लिए कम-से-कम 0.2 सेकंड विलंब) का समर्थन करता है
- उच्च-आवृत्ति वर्कफ़्लो और स्मूथ विंडो स्विचिंग के लिए अनुकूलित
- local-first डिज़ाइन, बिना किसी डिफ़ॉल्ट क्लाउड व्यवहार विश्लेषण निर्भरता के

## वेबसाइट

- Zeabur होमपेज: https://telunkey.zeabur.app

> [!IMPORTANT]
> यदि आप Zeabur तक लगातार नहीं पहुंच पा रहे हैं, तो संभवतः आपके पास TelunKey के उपयोग का कोई परिदृश्य नहीं होगा। लेकिन यदि आपके पास नेटवर्क समस्याओं को हल करने की क्षमता और धैर्य है, तो आपको निश्चित रूप से TelunKey आज़माना चाहिए—मुझे पूरा विश्वास है कि यह आपकी उत्पादकता में उल्लेखनीय सुधार करेगा।

## यूआई पूर्वावलोकन

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<img alt="ट्रिगर संकेत" src="./images/datishi.png?v=20260329" width="100%" />
<img alt="Chrome परिदृश्य" src="./images/chrome.png?v=20260329" width="100%" />
<img alt="सेटिंग्स स्क्रीन" src="./images/shezhi.png?v=20260329" width="100%" />

## सिस्टम आवश्यकताएं

- macOS 14.0 या बाद का संस्करण

## स्थापना

जिन उपयोगकर्ताओं के पास [Homebrew](https://brew.sh/) स्थापित है, वे यह चला सकते हैं:

```bash
brew install --cask telungit/tap/telunkey
```

स्थापना के बाद, "एप्लिकेशन्स" (Applications) से TelunKey खोलें।

## अपडेट करना

```bash
brew upgrade --cask --greedy telungit/tap/telunkey
```

आप ऐप के भीतर भी अपडेट की जांच कर सकते हैं।

## अनुमतियाँ

TelunKey को पूर्ण कार्यक्षमता के लिए निम्नलिखित अनुमतियों की आवश्यकता है:

- अभिगम्यता: वैश्विक कीबोर्ड घटनाओं को सुनें
- स्क्रीन रिकॉर्डिंग: विंडो थंबनेल जेनरेट करें

## गोपनीयता

TelunKey local-first रणनीति का पालन करता है। मुख्य डेटा आपके डिवाइस पर ही रहता है।

## प्रतिक्रिया

- Telegram: https://t.me/telungram
