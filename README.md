<!-- 🚀 Telegram Action for GitHub -->
<p align="center">
  <img src="https://img.shields.io/badge/Telegram_Action-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Action" width="350" />
</p>

<h1 align="center">
  <span style="color:#2AABEE;" dir="ltr">Telegram Action</span> for GitHub<br>
  <span style="color:#2AABEE;" dir="rtl">اکشن تلگرام</span> برای گیت‌هاب
</h1>
<h3 align="center">
  <span dir="ltr">Download files & archive channel posts — directly in your repo, with one click!</span><br>
  <span dir="rtl">دانلود فایل از تلگرام + بایگانی پست‌های کانال، همه با یک کلیک!</span>
</h3>

<p align="center">
  <img src="https://img.shields.io/badge/version_1.0-blueviolet?style=flat-square" alt="version" />
  <img src="https://img.shields.io/badge/telegram-2CA5E0?style=flat-square&logo=telegram&logoColor=white" alt="telegram" />
  <img src="https://img.shields.io/badge/github_actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="github actions" />
  <img src="https://img.shields.io/badge/license_MIT-brightgreen?style=flat-square" alt="license" />
</p>

---

## ✨ <span dir="ltr">What does this action do?</span> / <span dir="rtl">این اکشن چه کاری انجام می‌دهد؟</span>

- <p dir="ltr"><strong>📥 Download a file from Telegram</strong><br>Give it a message link or ID, and the file lands in <code>downloads/</code> with its original name.</p>
  <p dir="rtl"><strong>📥 دانلود فایل از تلگرام</strong><br>لینک یا شناسهٔ پیام را که بدهی، فایل با نام اصلی‌اش در پوشهٔ <code>downloads</code> ذخیره می‌شود.</p>

- <p dir="ltr"><strong>🗂️ Save recent posts from a channel</strong><br>Provide a channel ID and the number of posts you want — they'll be stored as neat JSON files inside <code>posts/</code>.</p>
  <p dir="rtl"><strong>🗂️ ذخیرهٔ آخرین پست‌های کانال</strong><br>شناسهٔ عددی کانال و تعداد پست‌های مورد نظرت را بده؛ هر پست به صورت یک فایل JSON مرتب در <code>posts</code> بایگانی می‌شود.</p>

<p dir="ltr">No tokens, no bots, no complex setup. Just pure automation.</p>
<p dir="rtl">بدون نیاز به توکن، بدون ربات، بدون هیچ تنظیمات اضافی. فقط خودکارسازی خالص.</p>

---

## 🚀 <span dir="ltr">How to use</span> / <span dir="rtl">چطور استفاده کنم</span> (3 simple steps / سه قدم کوتاه)

### 1. <span dir="ltr">Fork this repository 🍴</span> / <span dir="rtl">ریپازیتوری را فورک کن</span>
<p dir="ltr">Click the <strong>Fork</strong> button and bring the project into your own GitHub account.</p>
<p dir="rtl">دکمهٔ <strong>Fork</strong> را بزن تا پروژه به اکانت گیت‌هاب خودت منتقل شود.</p>

### 2. <span dir="ltr">Run the workflow ▶️</span> / <span dir="rtl">اکشن را اجرا کن</span>
- <p dir="ltr">Go to the <strong>Actions</strong> tab in your forked repo.</p>
  <p dir="rtl">از بالای ریپازیتوری وارد تب <strong>Actions</strong> شو.</p>
- <p dir="ltr">Select the workflow named <strong>"Telegram Magic"</strong> (or whatever it's titled).</p>
  <p dir="rtl">Workflowای به نام <strong>"اجرای اکشن تلگرام"</strong> (یا هر عنوانی که دارد) را انتخاب کن.</p>
- <p dir="ltr">Click <strong>Run workflow</strong>.</p>
  <p dir="rtl">روی <strong>Run workflow</strong> کلیک کن.</p>
- <p dir="ltr">Fill in the required inputs:</p>
  <p dir="rtl">حالا اطلاعات خواسته‌شده را پر کن:</p>

| <span dir="ltr">What you want</span> / <span dir="rtl">کاری که می‌خواهی</span> | <span dir="ltr">What to enter</span> / <span dir="rtl">چی وارد کنی</span> | <span dir="ltr">Example</span> / <span dir="rtl">مثال</span> |
|----------------------------------|----------------------------|---------------|
| <span dir="ltr"><strong>Download a file</strong></span> / <span dir="rtl"><strong>دانلود فایل</strong></span> | <span dir="ltr">Paste the full message link (<code>https://t.me/...</code>) <strong>or</strong> provide the chat ID and message ID.</span><br><span dir="rtl">لینک کامل پیام را بچسبان <strong>یا</strong> شناسهٔ چت و شناسهٔ پیام را بده.</span> | `https://t.me/c/123456/42` |
| <span dir="ltr"><strong>Fetch channel posts</strong></span> / <span dir="rtl"><strong>دریافت پست‌های کانال</strong></span> | <span dir="ltr">Enter the numeric channel ID (with <code>-</code>) and the number of recent posts you'd like. <strong>Any number works!</strong></span><br><span dir="rtl">شناسهٔ عددی کانال (با علامت <code>-</code>) و تعداد پست‌هایی که می‌خواهی را وارد کن. <strong>هر عددی قبول است!</strong></span> | `-1001234567890` and `50` |

### 3. <span dir="ltr">Wait & receive 🎁</span> / <span dir="rtl">صبر کن و دریافت کن</span>
<p dir="ltr">The action kicks off and usually finishes in under a minute.</p>
<p dir="rtl">اکشن شروع به کار می‌کند و معمولاً کمتر از یک دقیقه تمام می‌شود.</p>

<p dir="ltr">Once done, the results are ready:</p>
<p dir="rtl">بعد از اتمام کار، نتیجه‌ها اینجا هستند:</p>
- <span dir="ltr">Downloaded file(s) → <strong><code>downloads/</code></strong> folder</span><br>
  <span dir="rtl">فایل‌های دانلودی → پوشهٔ <strong><code>downloads</code></strong></span>
- <span dir="ltr">Fetched posts → <strong><code>posts/</code></strong> folder (each post saved as <code>post_&lt;id&gt;.json</code>)</span><br>
  <span dir="rtl">پست‌های دریافت‌شده → پوشهٔ <strong><code>posts</code></strong> (هر پست به صورت <code>post_&lt;id&gt;.json</code>)</span>

<p dir="ltr">That’s it! No secrets, no logins — just you, Telegram, and GitHub Actions.</p>
<p dir="rtl">همین! بدون هیچ راز یا ورود به حسابی — فقط تو، تلگرام و گیت‌هاب اکشنز.</p>

---

## 📂 <span dir="ltr">Output structure</span> / <span dir="rtl">ساختار خروجی</span>
<pre dir="ltr">
📁 downloads/
   └── example.pdf          # original file name
</pre>
<pre dir="rtl">
📁 downloads/
   └── example.pdf          # نام اصلی فایل
</pre>

<pre dir="ltr">
📁 posts/
   ├── post_101       # text, captions, photos, dates
   └── ...
</pre>
<pre dir="rtl">
📁 posts/
   ├── post_101       # متن، کپشن، عکس، تاریخ
   └── ...
</pre>

---

## 💡 <span dir="ltr">Pro tips</span> / <span dir="rtl">نکات طلایی</span>

- <p dir="ltr">The channel must be <strong>public</strong> (or accessible without authentication).</p>
  <p dir="rtl">کانال باید <strong>عمومی</strong> باشد (یا بدون احراز هویت قابل خواندن).</p>

- <p dir="ltr">You can schedule the workflow to run automatically using GitHub’s cron feature.</p>
  <p dir="rtl">می‌توانی با زمان‌بندی گیت‌هاب (cron) این فرایند را کاملاً خودکار کنی.</p>

- <p dir="ltr">Want to fetch the last 200 posts? Go for it! The number is entirely up to you.</p>
  <p dir="rtl">می‌خواهی ۲۰۰ پست آخر را بگیری؟ برو جلو! تعداد کاملاً به انتخاب خودت است.</p>

---

<p align="center">
  <span dir="ltr">Made with ☕ and a love for automation | Always connected, like Telegram 💙</span><br>
  <span dir="rtl">ساخته‌شده با ☕ و عشق به خودکارسازی | همیشه متصل، مثل تلگرام 💙</span>
</p>
