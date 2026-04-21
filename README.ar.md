# TelunKey
[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

TelunKey هو مشغل اختصارات أصلي لنظام macOS ينجز تفعيل التطبيقات واختيار النوافذ ضمن تسلسل مفاتيح واحد.

- مطور بلغة Swift الأصلية لاستجابة سريعة واستهلاك منخفض وتداخل أقل
- يدعم Command الأيسر/الأيمن (تأخير 0 أو مخصص)، وOption الأيسر/الأيمن (تأخير 0 أو مخصص)، وتفعيل Space (حد أدنى 0.2 ثانية لتجنب التأثير على الكتابة اليومية)
- مُحسّن لسير العمل عالي التكرار ولتنقّل أكثر سلاسة بين النوافذ
- تصميم local-first دون اعتماد افتراضي على تحليلات السلوك السحابية

## موقع إلكتروني

- صفحة زيبور الرئيسية: https://telunkey.zeabur.app

> [!IMPORTANT]
> إذا لم تتمكن من الوصول إلى Zeabur على الإطلاق، فقد لا يناسب TelunKey بيئتك الحالية. إذا كان بإمكانك حل مشكلات الشبكة من جانبك، فإن TelunKey يستحق المحاولة ويمكنه تحسين كفاءتك.

## معاينة واجهة المستخدم

https://github.com/user-attachments/assets/bf6afeee-3813-410c-87db-9696f364cea7

<img alt="تلميح التفعيل" src="./images/datishi.png?v=20260329" width="100%" />
<img alt="سيناريو Chrome" src="./images/chrome.png?v=20260329" width="100%" />
<img alt="شاشة الإعدادات" src="./images/shezhi.png?v=20260329" width="100%" />

## متطلبات النظام

- macOS 14.0 أو أحدث

## تحميل

- أحدث إصدار (DMG): https://github.com/telungit/TelunKey/releases/latest/download/TelunKey.dmg
- جميع الإصدارات: https://github.com/telungit/TelunKey/releases

## تثبيت

1. قم بتنزيل وفتح "TelunKey.dmg".
2. اسحب "TelunKey.app" إلى التطبيقات
3. لا تفتح التطبيق بعد. انقر أولاً نقراً مزدوجاً على `2. Run Once After Install.command` داخل DMG
4. افتح TelunKey بعد اكتمال الإصلاح
5. شغّل الأمر التالي يدويًا في الطرفية فقط إذا فشل السكربت

```bash
xattr -dr com.apple.quarantine /Applications/TelunKey.app
```

## الأذونات

يتطلب TelunKey الأذونات التالية للحصول على الوظائف الكاملة:

- إمكانية الوصول: مراقبة أحداث لوحة المفاتيح العامة
- تسجيل الشاشة: إنشاء صور مصغرة للنوافذ

## خصوصية

يتبع TelunKey إستراتيجية محلية أولاً. تبقى البيانات الأساسية على جهازك.

## ملاحظات

- Telegram: https://t.me/telungram
