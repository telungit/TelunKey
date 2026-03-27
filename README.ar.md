# TelunKey
[简体中文](./README.md) | [繁體中文](./README.zh-Hant.md) | [English](./README.en.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md) | [Español](./README.es.md) | [Português](./README.pt.md) | [हिन्दी](./README.hi.md) | [Русский](./README.ru.md) | [Français](./README.fr.md) | [Deutsch](./README.de.md) | [العربية](./README.ar.md)

TelunKey هو مشغل اختصارات أصلي لنظام macOS ينجز تفعيل التطبيقات واختيار النوافذ ضمن تسلسل مفاتيح واحد.

- مطور بلغة Swift الأصلية لاستجابة سريعة واستهلاك منخفض وتداخل أقل
- يدعم Command الأيسر/الأيمن (تأخير 0 أو مخصص)، وOption الأيسر/الأيمن (تأخير 0 أو مخصص)، وتفعيل Space (حد أدنى 0.2 ثانية لتجنب التأثير على الكتابة اليومية)
- مُحسّن لسير العمل عالي التكرار ولتنقّل أكثر سلاسة بين النوافذ
- تصميم local-first دون اعتماد افتراضي على تحليلات السلوك السحابية

## موقع إلكتروني

- صفحة زيبور الرئيسية: https://telunkey.zeabur.app

> [!هام]
> إذا لم تتمكن من الوصول إلى Zeabur على الإطلاق، فقد لا يناسب TelunKey بيئتك الحالية. إذا كان بإمكانك حل مشكلات الشبكة من جانبك، فإن TelunKey يستحق المحاولة ويمكنه تحسين كفاءتك.

## معاينة واجهة المستخدم

https://github.com/user-attachments/assets/762f43e0-eac3-4ffa-ba33-f68f720d2627

![Trigger hint](./images/datishi.png)
![Chrome scenario](./images/chrome.png)
![Settings](./images/shezhi.png)

## متطلبات النظام

- macOS 14.0 أو أحدث

## تحميل

- أحدث إصدار (DMG): https://github.com/telungit/TelunKey/releases/latest/download/TelunKey.dmg
- جميع الإصدارات: https://github.com/telungit/TelunKey/releases

## تثبيت

1. قم بتنزيل وفتح "TelunKey.dmg".
2. اسحب "TelunKey.app" إلى التطبيقات
3. بعد التثبيت، انقر نقرًا مزدوجًا فوق `一键修复.command` داخل DMG (يقوم تلقائيًا بتشغيل الأمر أدناه):

```bash
xattr -dr com.apple.quarantine /Applications/TelunKey.app
```

4. فقط في حالة فشل البرنامج النصي، قم بتشغيل الأمر التالي يدويًا في الوحدة الطرفية
5. أعد تشغيل TelunKey

## الأذونات

يتطلب TelunKey الأذونات التالية للحصول على الوظائف الكاملة:

- إمكانية الوصول: مراقبة أحداث لوحة المفاتيح العامة
- تسجيل الشاشة: إنشاء صور مصغرة للنوافذ

## خصوصية

يتبع TelunKey إستراتيجية محلية أولاً. تبقى البيانات الأساسية على جهازك.

## ملاحظات

- Telegram: https://t.me/telungram
