# قالب لاتک رساله دکتری دانشگاه تهران (نسخهٔ سفارشی)

**ناشر / نگهدارندهٔ این نسخه:** شهریار توقی

LaTeX template for MSc/BSc/PhD theses of University of Tehran.

قالب لاتک پایان‌نامه / رسالهٔ دانشگاه تهران

---

## منبع اصلی

این پروژه بر پایهٔ قالب متن‌باز **tehran-thesis** اثر **سینا ممکن** ساخته شده است:

- مخزن اصلی: [https://github.com/sinamomken/tehran-thesis](https://github.com/sinamomken/tehran-thesis)
- توضیح رسمی قالب پایه: *LaTeX template for BSc/MSc/PhD theses of University of Tehran — قالب لاتک پایان‌نامه دانشگاه تهران*

کپی اولیه را می‌توانید از همان مخزن بگیرید:

```bash
git clone https://github.com/sinamomken/tehran-thesis --single-branch
```

این نسخهٔ حاضر، توسط **شهریار توقی** برای رسالهٔ دکتری در **دانشکدگان علوم و فناوری‌های میان‌رشته‌ای** دانشگاه تهران سفارشی‌سازی و مستند شده است.

---

<div dir="rtl">

## راهنمای فارسی

### ویژگی‌ها

1. منطبق با فایل ورد «دستورالعمل نگارش و تدوین پایان‌نامه» دانشگاه تهران، شهریور ۱۴۰۵ (و ساختار پیشنهادی دانشکدهٔ میان‌رشته‌ای).
2. طراحی مدولار و انعطاف‌پذیر، به همراه دستورات از پیش‌تعریف‌شده برای مشخصات متغیر یک پایان‌نامه / رسالهٔ دانشگاه تهران (مثل عنوان، نام دانشجو، استاد راهنما، تاریخ و غیره).
3. استفاده از قلم‌های استاندارد سری X نسخهٔ ۲ یا قلم‌های استاندارد سری IRFonts اثر شورای عالی اطلاع‌رسانی (به‌جای قلم‌های غیراستاندارد BFonts).
4. ساخته‌شده بر اساس قالب‌های پیشرفتهٔ IUST-Thesis و HSU-Thesis-V1 اثر دکتر محمود امین‌طوسی، و قالب tehran-thesis اثر سینا ممکن.
5. حاوی اسکلت موضوعی فصول و نکات لازم برای نوشتن رسالهٔ دکتری (در حوزهٔ شناسایی و بازسازی کور کدهای توربو به‌عنوان نمونهٔ جاری).
6. قابلیت انتخاب سبک‌های ارجاع‌دهی فارسی گوناگون؛ در این نسخهٔ سفارشی سبک پیش‌فرض **IEEE** (`ieeetr-fa`) است.
7. مدیریت هوشمند واژه‌نامه‌ها و درج اصطلاحات تخصصی، با استفاده از بستهٔ `glossaries` و موتور `xindy`.
8. قابلیت حاشیه‌نویسی مستقیم در فایل‌های TeX در حالت پیش‌نویس، با استفاده از بستهٔ `todonotes`.
9. امکان درج شکل‌ها، جداول، نمودارهای `tikz`، الگوریتم‌های فارسی و لاتین و کدهای رنگی؛ به‌علاوهٔ فهرست‌هایی از آن‌ها.
10. سربرگ استاندارد بدون هم‌پوشانی عنوان فصل و عنوان رساله، حاشیهٔ مناسب یک‌رو/دورو، و شماره‌دهی صفحات منطبق بر دستورالعمل نگارش.
11. پشتیبانی از پانوشت دوجهته: فارسی RTL با `\footnote` و انگلیسی LTR با `\LTRfootnote`.

### تغییرات این نسخه نسبت به قالب اولیه (tehran-thesis)

نسبت به نسخهٔ اولیهٔ [سینا ممکن](https://github.com/sinamomken/tehran-thesis)، ساختار محتوایی و داده‌ای رساله به‌صورت زیر تغییر کرده است:

| بخش | قالب اولیه | این نسخه |
| --- | --- | --- |
| مقطع پیش‌فرض | نمونهٔ کارشناسی ارشد (`msc`) و راهنمای لاتک | رسالهٔ دکتری (`phd`) |
| دانشکده | پردیس دانشکده‌های فنی / علوم مهندسی | دانشکدگان علوم و فناوری‌های میان‌رشته‌ای |
| تعداد فصول | ۵ فصل عمومی (مقدمه، مرور ادبیات، روش، نتایج، نتیجه‌گیری) | **۸ فصل** موضوعی برای رسالهٔ بازسازی کور کد توربو |
| محتوای فصول | راهنمای استفاده از لاتک | اسکلت پژوهشی با عناوین و راهنمای کوتاه هر زیربخش |
| صفحات آغازین | جلد، بسم‌الله، عنوان، داوران، اصالت، تقدیم، تقدیر، چکیده | همان‌ها به‌علاوهٔ **چکیده گرافیکی**، **نتیجهٔ تشابه‌یابی**، **سوگندنامهٔ دکتری**، **تأمین اعتبار** |
| ترتیب بخش پایانی | مراجع ← پیوست‌ها ← واژه‌نامه | **منابع علمی** ← واژه‌نامه‌ها ← پیوست‌ها ← چکیده/عنوان انگلیسی |
| سبک مراجع | `plain-fa` (نمونه) | `ieeetr-fa` (IEEE) با عنوان «منابع علمی» |
| شماره‌گذاری | جداکنندهٔ پیش‌فرض زی‌پرشین | `\SepMark{-}` → بخش‌ها به صورت `1-2-3`؛ شکل/جدول/رابطه به صورت `فصل-شماره` |
| سربرگ | عنوان کامل رساله + عنوان فصل هم‌زمان (امکان تداخل) | صفحات فرد: عنوان فصل؛ صفحات زوج: `\runningtitle` کوتاه |
| واژه‌نامه / اختصار | نمونهٔ عمومی | بذر اصطلاحات حوزهٔ توربو / بازسازی کور |
| پیوست‌ها | آموزش لاتک | اسکلت مطالب تکمیلی رساله |
| نمونهٔ شکل | — | شکل نمونه در فصل ۱ با `\includegraphics` و ارجاع `\ref` |

همچنین دستورات جدیدی به کلاس/`faTitle` افزوده شده‌اند، از جمله:

- `\runningtitle{...}` برای عنوان کوتاه سربرگ
- `\graphicalabstract{...}`، `\similarityresult{...}`، `\fundingtext{...}`
- صفحات `\graphicalAbstractPage`، `\similarityPage`، `\oathPage`، `\fundingPage`

### ساختار پوشه‌ها و فایل‌های مهم

```text
main.tex                 ← فایل اصلی کامپایل
build.sh / latexmkrc     ← ساخت خودکار
tex/
  tehran-thesis.cls      ← کلاس قالب
  commands.tex           ← بسته‌ها، فونت، سربرگ، شماره‌گذاری
  faTitle.tex            ← مشخصات فارسی، چکیده، صفحات ویژه
  enTitle.tex            ← مشخصات و چکیدهٔ انگلیسی
  thesis_preamble.tex    ← ترتیب صفحات آغازین و فهرست‌ها
  chapter1.tex … chapter8.tex
  appendix1.tex … appendix3.tex
  MyReferences.bib
  words.tex / acronyms.tex / glossaries-settings.tex
img/                     ← تصاویر (مثلاً turbo-structure-sample.png)
font/                    ← قلم‌های همراه قالب
```

### چگونه استفاده کنیم؟

1. مشخصات فردی را در `tex/faTitle.tex` و `tex/enTitle.tex` پر کنید (نام، استادان، گروه، تاریخ، چکیده، کلیدواژه، `\runningtitle`).
2. متن هر فصل را در `tex/chapterN.tex` بنویسید؛ عناوین زیربخش‌ها از قبل گذاشته شده‌اند.
3. مراجع را در `tex/MyReferences.bib` وارد کنید و در متن با `\cite{...}` ارجاع دهید.
4. واژه‌ها و اختصارها را در `tex/words.tex` و `tex/acronyms.tex` تعریف کنید.
5. تصاویر را در `img/` بگذارید و مانند نمونهٔ فصل ۱ درج کنید:

```latex
شکل~\ref{fig:turbo-structure-sample} ... را نشان می‌دهد.

\begin{figure}[ht]
  \centering
  \includegraphics[width=0.85\textwidth]{turbo-structure-sample}
  \caption{...}
  \label{fig:turbo-structure-sample}
\end{figure}
```

6. پانوشت فارسی و انگلیسی:

```latex
متن فارسی\footnote{توضیح فارسی RTL.}
و معادل\LTRfootnote{English LTR footnote.}
```

#### کامپایل

از ریشهٔ پروژه:

```bash
./build.sh
```

یا با `latexmk`:

```bash
latexmk -bibtex -pdf main.tex
```

خروجی: `main.pdf`

#### پیش‌نیازها

- نصب کامل `texlive` (لینوکس/ویندوز) یا `MacTeX` (مک)، به‌ویژه:
  - زی‌پرشین (`XePersian`)
  - `persian-bib`
  - `glossaries`
  - `todonotes`
- `latexmk`
- `bibtex` / `bibtex8` (برای سبک‌های فارسی)
- `xindy` با زبان `persian` یا `persian-variant3`
- ویرایشگر با پشتیبانی RTL (مثلاً BiDiTexmaker یا TeX در VS Code / Cursor)
- \[اختیاری\] نصب قلم‌های سری X نسخهٔ ۲ و Junicode در سیستم

</div>

## English Readme

### Maintainer of this fork

**Shahryar Tooghi** (`شهریار توقی`)

### Upstream

Based on [sinamomken/tehran-thesis](https://github.com/sinamomken/tehran-thesis) by **Sina Momken** — *LaTeX template for MSc/BSc/PhD theses of University of Tehran*.

### Features (this customized edition)

1. Aligned with the University of Tehran thesis writing guide (Word template, Shahrivar 1405 / 2026) and an 8-chapter PhD outline for blind turbo-code reconstruction.
2. Modular design with predefined commands for thesis metadata (title, student name, supervisor, date, …).
3. Standard X Series 2 or IRFonts (SCICT), not BFonts.
4. Descended from IUST-Thesis / HSU-Thesis-V1 (Mahmood AminToosi) via tehran-thesis (Sina Momken).
5. Chapter skeletons with short guidance notes instead of a LaTeX tutorial body.
6. Default bibliography style `ieeetr-fa` (IEEE), section title «منابع علمی».
7. Glossaries via `glossaries` + `xindy`.
8. Draft annotations via `todonotes`.
9. Figures, tables, TikZ, algorithms, listings, and their lists.
10. Non-overlapping running headers (odd: chapter; even: short `\runningtitle`).
11. Extra front-matter pages: graphical abstract, similarity report, PhD oath, funding statement.
12. Bidirectional footnotes: Persian `\footnote` (RTL) and English `\LTRfootnote` (LTR).

### Structural changes vs. upstream

- Default class option: `phd` (not sample `msc`).
- Faculty metadata for College of Interdisciplinary Sciences and Technologies.
- Eight topical chapters (`chapter1`–`chapter8`) instead of five generic guide chapters.
- Back-matter order: bibliography → glossaries → appendices → English abstract/title.
- Chapter/figure/table/equation numbering with Persian dash separators (`1-2`, `1-1`, …).
- New macros/pages for graphical abstract, similarity, oath, funding, and running title.
- Sample figure workflow under `img/` referenced from Chapter 1.

### How to use

1. Edit `tex/faTitle.tex` and `tex/enTitle.tex`.
2. Write content in `tex/chapter1.tex` … `tex/chapter8.tex`.
3. Manage references in `tex/MyReferences.bib`.
4. Build with `./build.sh` or `latexmk -bibtex -pdf main.tex`.

### Prerequisites

Full TeX Live / MacTeX with XePersian, persian-bib, glossaries, todonotes, latexmk, bibtex/bibtex8, and xindy (`persian` / `persian-variant3`). An RTL-capable editor is recommended. Optional: system-installed X Series 2 and Junicode fonts.

### License

Upstream project is GPL-3.0 (see `LICENSE`). Retain attribution to Sina Momken and the original repository when redistributing.

---

**ناشر این نسخه:** شهریار توقی  
**منبع اصلی:** [https://github.com/sinamomken/tehran-thesis](https://github.com/sinamomken/tehran-thesis)
