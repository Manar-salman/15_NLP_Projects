# 🤖 Smart NLP System | نظام NLP الذكي

**Manar Salman**  
NLP Project — Graduation Course @2026

-----

## 📌 About | عن المشروع

**EN:** An intelligent NLP system built as a graduation project for the NLP course. It combines two powerful features: a RAG-based Q&A system that answers questions from any URL or text, and a translation comparison system between two models (Helsinki & mBART). Fully supports Arabic and English.

**AR:** نظام ذكي مبني كمشروع تخرج من مادة معالجة اللغات الطبيعية (NLP). يجمع بين ميزتين: نظام سؤال وجواب من روابط أو نصوص باستخدام تقنية RAG، ونظام ترجمة مع مقارنة بين نموذجين. يدعم العربي والإنجليزي بالكامل.

-----

## ✨ Features | المميزات

|Feature                     |الميزة                  |
|----------------------------|------------------------|
|Q&A from URL or text        |سؤال وجواب من رابط أو نص|
|Compare 2 LLM models        |مقارنة بين نموذجين      |
|Arabic ↔ English translation|ترجمة عربي وإنجليزي     |
|Compare Helsinki vs mBART   |مقارنة نموذجي الترجمة   |
|Bilingual interface         |واجهة ثنائية اللغة      |

-----

## 🔑 API Key Setup | إعداد المفتاح

> ⚠️ **المفتاح لا يُحفظ في الكود — كل مستخدم يحط مفتاحه الخاص**  
> ⚠️ **The API Key is NOT stored in the code — each user must add their own key**

1. سجّل مجاناً على | Register for free at 👉 [console.groq.com](https://console.groq.com)
1. أنشئ مفتاح جديد من | Create a new key from **API Keys → Create API Key**
1. في الخلية الأولى من الكود حط مفتاحك | In Cell 1, add your key:

```python
GROQ_API_KEY = "your_key_here"  # ← حط مفتاحك هنا
```

-----

## 🚀 How to Run | طريقة التشغيل

1. افتح الملف في Google Colab | Open the notebook in Google Colab
1. حط مفتاح Groq في الخلية الأولى | Add your Groq API Key in Cell 1
1. شغّل الخلية الأولى وانتظر تحميل النماذج | Run Cell 1 and wait for models to load
1. شغّل الخلية الثانية | Run Cell 2
1. استخدم التبويبين | Use the two tabs ✅

-----

## 🛠️ Models Used | النماذج المستخدمة

|النموذج                       |الاستخدام                            |
|------------------------------|-------------------------------------|
|LLaMA 3.3 70B (Groq)          |سؤال وجواب — Q&A                     |
|LLaMA 3.1 8B (Groq)           |سؤال وجواب مقارنة — Q&A Comparison   |
|Helsinki-NLP/opus-mt          |ترجمة — Translation                  |
|Facebook mBART-50             |ترجمة مقارنة — Translation Comparison|
|paraphrase-multilingual-MiniLM|تضمين النص — Text Embedding          |

-----
