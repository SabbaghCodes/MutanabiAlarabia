# Mutanabi' Alarabia (متنبئ العربية)

**First Platform Dedicated to Students and Researchers, providing a comprehensive analysis of words from all perspectives a student may need, delivered at the click of a button and in the blink of an eye.**

![Mutanabi' Alarabia](path/to/mutanabi_screenshot.png)

After studying existing solutions and the challenges faced by their users, we arrived at our creative solution - **Mutanabi' Alarabia**. It is the first platform dedicated to students and researchers, offering a complete analysis of words from all the angles a student might require. This analysis is provided with a simple click, instantly.‎

## النموذج (The Model)

We employed the model (a system of models) to perform six key operations in Arabic language processing:

### 1. Summarization (التلخيص)

It effectively summarizes paragraphs while preserving the original meaning and incorporating all the essential ideas from the main paragraphs. We utilized TF-IDF for word frequency calculation and the Text Ranking algorithm for normalization.
يقوم بتلخيص الفقرات تلخيص فعال  مع المحافظة على المعنى الأصلي و احتواءه على جميع الأفكار الأساسية من الفقرات الرئيسية بحيث استخدمنا (TF-IDF) لحساب ال frequency للكلمات و تطبيع خوارزمية Text Ranking.

### 2. Morphological Analysis (التشكيل)

We developed a model that aids in morphological analysis, taking into account the positions of words in sentences (their grammatical inflections).
بحيث طورنا موديل يساعد على التشكيل آخذاً بعين الاعتبار موقع الكلمات بالجمل (اعرابها).

### 3. Autocorrection (التصحيح التلقائي)

The model identifies duplicate words, assigns specific repetitions for each word, and calculates the probability of each word's appearance. If there are words that need correction, this program cleans up the words, removes extra letters, replaces any incorrect letters with their correct synonyms, and finally replaces the correct word instead of the erroneous one.
سيقوم النموذج بإيجاد الكلمات المكررة ووضع تكرارات معين لكل كلمة ثم يقوم بحساب احتمالية ظهور كل كلمة 
اذا كانت هنالك كلمات بحاجة للتعديل فيقوم هذا البرنامج بتنظيف الكلمات وحذف الحروف الزائدة وتبديل أية حروف خاطئة بمرادفها الصحيح وفي آخر خطوة يتم تبديل  الكلمة الصحيحة بدلاً من الكلمة التي كانت تحوي أخطاء.

### 4. Lexical Extractor (مستخرج)

A model that helps extract the morphological root and stem, grammatical categories, and conjugations if present.
نموذج يساعد على استخراج الاصل المعجمي و الجذر ، اقسام الكلام جمع التكسير ان وجد.

### 5. Predictor (متنبئ)

It suggests and predicts speech at a specific location in the sentence.
بحيث يقترح و يتوقع الكلام في مكان محدد من الجملة.

### 6. Dialect Classifier (مصنف اللهجات)

It classifies Arabic dialects and identifies 25 dialects, including Jordanian, Saudi, Egyptian, and Moroccan.
يقوم بتصنيف اللهجات العربية و تحديدها ل ٢٥ لهجة منها ( الاردنية ، السعودية ، المصرية ، المغربية).

The artificial intelligence model was implemented as a Chrome extension for easy use by various users when needed.

To view the application, watch the video [here](https://drive.google.com/file/d/14frXMRIprI6tzjnQxnbIhE-vqKltVuhv/view?usp=sharing).

To see an example of model testing, click [here](https://drive.google.com/file/d/1nlbFKCzSqSz9n7FGSPmAG9Iyn0QonR43/view?usp=sharing).
