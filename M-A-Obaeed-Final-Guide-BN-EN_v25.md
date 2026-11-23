# M A Obaeed — Final All-in-One GitHub Upload Guide v25

## নিজস্ব favicon, README-বিহীন একটি ZIP / One clean ZIP

এই সংস্করণে **site, original photos, optimized previews, নিজস্ব MO favicon এবং MD guide—সব একটি ZIP-এ** দেওয়া হয়েছে। `UPLOAD-README.txt` এবং `audio/`, `videos/`, `documents/`-এর README ফাইল বাদ দেওয়া হয়েছে। ZIP-টি 100MB-এর নিচে।

1. `portfolio-upload-v25-all-in-one.zip` download করে **Extract All / Unzip** করুন।
2. `obaeedma.github.io` repository-র root খুলুন, যেখানে আগের `index.html` আছে।
3. **Add file → Upload files** খুলুন।
4. Extract করা folder-এর **ভিতরের সব file ও folder একসঙ্গে select** করে upload করুন। বাইরের wrapper folder বা ZIP নিজে upload করবেন না।
5. আগের `favicon.ico` থাকলে repository-তে সেটি delete করুন; নতুন `favicon.svg` ও `index.html` একসঙ্গে থাকবে। অন্য কোনো existing folder delete করবেন না।
6. নাম, বড়/ছোট অক্ষর ও folder বিন্যাস বদলাবেন না। **Commit changes** দিন।
7. Actions-এ deployment শেষ হলে live site refresh/private window-তে খুলুন। Browser tab-এ Lovable-এর বদলে MO monogram দেখা যাবে।

**English:** Unzip the all-in-one package first. Select every extracted file and folder together, upload them to the repository root, and commit. Remove the old favicon.ico if present; keep the new favicon.svg beside index.html. No README files are included. GitHub does not automatically extract an uploaded ZIP.

আগের v23 three-part নির্দেশনা শুধু fallback। GitHub এই all-in-one upload গ্রহণ না করলে সেই তিনটি part ব্যবহার করুন; সেই পুরোনো part-গুলোতে পুরোনো favicon ও README থাকতে পারে।

---

# সংরক্ষিত v23 নির্দেশিকা / Archived v23 guide

# M A Obaeed — Final GitHub Upload Guide v23 / চূড়ান্ত আপলোড নির্দেশিকা

## 100MB সমস্যার সমাধান: ৩টি ছোট ZIP / Three small upload parts

এই সংস্করণটি GitHub web upload-এর সুবিধার জন্য ৩টি ZIP-এ ভাগ করা। **তিনটি ZIP-ই download করুন, একবারে একটি করে Extract All / Unzip করুন এবং নিচের ক্রমে upload করুন।** ZIP file নিজে GitHub-এ upload করবেন না। প্রতিটি ZIP 25MB-এর নিচে এবং 100 file-এর নিচে।

| ক্রম | ZIP | যা upload করবেন |
|---|---|---|
| 1 | `portfolio-upload-v23-part-1.zip` | ভিতরের `index.html`, `photos/`, MD guide এবং অন্যান্য file/folder |
| 2 | `portfolio-upload-v23-part-2.zip` | ভিতরের `photos/` folder |
| 3 | `portfolio-upload-v23-part-3.zip` | ভিতরের `photos/` folder |

### সঠিক ধাপ / Exact steps

1. নিজের `obaeedma.github.io` repository-র published branch-এর root খুলুন, যেখানে আগের `index.html` আছে।
2. **Part 1** extract করুন। Extract করা folder-এর **ভিতরের সব file/folder** select করে **Add file → Upload files**-এ দিন। `index.html` replace হবে। **Commit changes** দিন।
3. **Part 2** extract করুন। ভিতরের `photos/` folder একই repository root-এ upload করে **Commit changes** দিন। এটি `photos/optimized/`-এর প্রথম অংশ যোগ করবে।
4. **Part 3** extract করুন। ভিতরের `photos/` folder আবার একই root-এ upload করে **Commit changes** দিন। এটি বাকি optimized album যোগ করবে।
5. কোনো existing `photos/`, `travel/`, `optimized/` বা অন্য folder **delete করবেন না**। Upload existing folder মুছে দেয় না; matching path-এর file যোগ/replace হয়।
6. **Actions**-এ Pages deployment সফল হলে live site খুলে refresh/private window-তে দেখুন।

**English:** Download and unzip all three parts. Upload the extracted contents of Part 1 to the repository root and commit. Then upload the extracted `photos/` folder from Part 2 and commit, followed by Part 3 and commit. Preserve every folder name and path. Never delete existing photo folders. Do not upload the ZIP files themselves.

## কেন ৩টি অংশ / Why three parts

- Part 1: মূল site, original JPEG photos, guide ও ছোট supporting files।
- Part 2: দ্রুত লোড হওয়া WebP previews-এর profile, projects, leadership এবং কয়েকটি travel album।
- Part 3: বাকি WebP travel previews (`sea-lakes`, `trails-friends`)।
- তিনটি অংশ একসঙ্গে v22-এর সম্পূর্ণ website content রাখে; কোনো ছবি বাদ দেওয়া হয়নি।

## Upload শেষে / After upload

- [ ] প্রথম ছবি, Profile, Projects, Leadership ও Travel thumbnails আসে।
- [ ] ছবি চাপলে বড় original photo viewer খুলে।
- [ ] `Explore by district`, district select ও next/previous কাজ করে।
- [ ] `photos/optimized/travel/trails-friends/` path-এর ছবিগুলো live site-এ 404 নয়।

Actual GitHub deployment এবং real iPhone/Safari এই package তৈরির সময় যাচাই করা হয়নি। Upload/deploy শেষে এই checklist অনুসরণ করুন।

---

# সংরক্ষিত v22 নির্দেশিকা / Archived v22 guide

নিচের v22 অংশ editing reference হিসেবে রাখা। **Upload পদ্ধতিতে উপরের v23 নির্দেশনাই প্রাধান্য পাবে; v22-এর একক ZIP upload নির্দেশনা আর প্রযোজ্য নয়।**

# M A Obaeed — Final GitHub Upload Guide v22 / চূড়ান্ত আপলোড নির্দেশিকা

## আগে এটি পড়ুন / Read this first

এই ZIP একটি সম্পূর্ণ upload-ready package। আগের v18/v19/v20/v21-এর আপলোড নির্দেশনার বদলে এই অংশ অনুসরণ করুন। নিচে পুরনো বিস্তারিত editing guide-ও রাখা হয়েছে; পুরনো “শুধু HTML upload” নির্দেশ এখন প্রযোজ্য নয়।

## ZIP-এর সঠিক বিন্যাস / Exact layout

```text
index.html
photos/
  optimized/       ← দ্রুত লোড হওয়া WebP previews
  profile/         ← original JPEGs
  projects/
  leadership/
  travel/
audio/
videos/
documents/
google05d55b660994bbbd.html
sitemap.xml
M-A-Obaeed-Final-Guide-BN-EN_v22.md
```

ZIP-এর ভিতরে extra wrapper folder নেই। Extract করার সময় আপনার computer একটি folder বানাতে পারে; সেই folder-এর **ভিতরের** file/folder upload করুন, বাইরের folder নয়। নাম, বড়/ছোট অক্ষর বা ভিতরের folder বিন্যাস বদলাবেন না। ZIP file নিজে GitHub-এ upload করবেন না।

## GitHub-এ আপলোড / Upload steps

1. `portfolio-upload-v22.zip` download করে **Extract All / Unzip** করুন।
2. নিজের `obaeedma.github.io` repository খুলুন। বর্তমান published branch-এর root-এ যান—যেখানে আগের `index.html` আছে।
3. **Add file → Upload files** খুলুন। Extract করা `index.html` এবং root-এর MD, sitemap ও Google verification file দিন। একই নামের file replace হবে।
4. একই root-এ `photos/`, `audio/`, `videos/`, `documents/` folder drag-and-drop করুন; folder-এর নাম এবং ভিতরের বিন্যাস অক্ষুণ্ণ রাখুন। **Commit changes** দিন। আগের কোনো folder মুছবেন না।
5. বেশি file-এর কারণে GitHub একসঙ্গে গ্রহণ না করলে ছোট batch-এ upload করুন। বিশেষ করে `photos/optimized/`-এ অনেক file আছে: GitHub-এ `photos/optimized/` খুলে তার ভিতরের `profile/`, `projects/`, `leadership/`, `travel/` একবারে একটি করে upload করুন। `travel/`-এর ক্ষেত্রেও দরকার হলে একবারে একটি album folder দিন। Existing folder না থাকলে folder-সহ root থেকে upload করলে path তৈরি হয়; সব file root-এ ছড়িয়ে দেবেন না।
6. **Actions**-এ Pages deployment সফল হওয়ার পরে live site খুলুন। Browser refresh বা private window ব্যবহার করুন।

**English:** Unzip first. Upload the extracted contents to the repository root, preserving all paths. Replace the existing `index.html`; retain the original JPEGs and upload the WebP previews as well. If the browser rejects a large batch, upload smaller folders at the corresponding repository path. This archive contains no repository metadata, dependencies or app build output.

## এই সংস্করণে কী আছে / What's included

- Dotong Pahar; Nafakhum ও Amiakhum আলাদা highlights।
- Sundarbans ও Saint Martin's Island আলাদা highlights।
- 64 জেলার compact, open/close district explorer।
- WebP previews: 480px ও 960px; বড় photo viewer-এ আসল JPEG।
- পুরনো original ছবি ও বর্তমান site-এর media folder সবই রাখা আছে।
- `audio/`, `videos/`, `documents/`-এর README নির্দেশনা media নয়; এখানে অনুপস্থিত নতুন audio/video/PDF যোগ করা হয়নি।

## নতুন ছবি যোগ বা পুরনো ছবি বদলালে / Future photo edits

পুরনো guide-এর JPEG-only thumbnail উদাহরণের বদলে বর্তমান `index.html`-এর পাশের working photo block অনুসরণ করুন। `href` original JPEG-এ থাকবে; `src` ও `srcset` matching WebP previews-এ থাকবে। শুধু JPEG বদলালে preview আপনা থেকে বদলাবে না—480px/960px WebP-ও নতুন করে তৈরি করে matching filename-এ upload করতে হবে। Generation script এই static upload package-এর অংশ নয়; project-এ `scripts/optimize-photos.py` রাখা আছে।

## আপলোডের পর পরীক্ষা / Live-site checklist

- [ ] প্রথম ছবি এবং Profile/Projects/Leadership-এর ছবি আসে।
- [ ] Travel album খুললে thumbnails আসে; ছবি চাপলে বড় ছবি আসে।
- [ ] `Explore by district` খুলে; district select ও next/previous কাজ করে।
- [ ] Light/dark switch, phone menu ও contact links কাজ করে।
- [ ] `photos/optimized/travel/portraits/portrait.480.webp` সরাসরি site URL-এ খুললে 404 নয়।
- [ ] `photos/travel/portraits/portrait.jpg` সরাসরি site URL-এ খুললে original ছবি আসে।

আগের automated checks ফোন/tablet/desktop মাপে করা হয়েছে। Actual iPhone/Safari বা আপনার GitHub deployment এই package তৈরির সময় যাচাই করা হয়নি; upload/deploy হওয়ার পরে উপরের checklist অনুসরণ করুন।

---

# সংরক্ষিত বিস্তারিত editing guide / Archived detailed editing guide

নিচের v18 editing guide reference হিসেবে রাখা হলো। Upload এবং photo-preview সংক্রান্ত নির্দেশনায় উপরের v22 অংশই প্রাধান্য পাবে।

# M A Obaeed — Portfolio Owner’s Complete Guide (v18)
## নিজের পোর্টফোলিও নিজে পরিচালনা করার পূর্ণাঙ্গ বাংলা–ইংরেজি নির্দেশিকা

**প্রস্তুতের তারিখ / Prepared:** 23 November 2026  
**প্রযোজ্য / Applies to:** v16: পূর্ণ জেলা-স্লাইড ও মানচিত্রসহ স্থির পোর্টফোলিও  
**ওয়েবসাইট / Website:** https://obaeedma.github.io/  
**সম্পাদনার জায়গা / Repository:** https://github.com/obaeedma/obaeedma.github.io

> এই একটি নির্দেশিকা কম্পিউটারে রেখে দিন। GitHub-এ রাখলে ফাইলের নামের ওপর ক্লিক করেও সুন্দরভাবে পড়তে পারবেন। `.md` মানে Markdown: সাধারণ লেখা, শিরোনাম ও কোডের উদাহরণ রাখার ফাইল। Notepad বা VS Code-এও খুলবে। এটি ওয়েবসাইটের নতুন কোড নয়; আপনার বর্তমান ওয়েবসাইট পরিচালনার বই।
>
> Keep this guide as your maintenance handbook. It documents your existing portfolio; it does not replace `index.html` or automatically add content.

---

## সূচি / Contents

1. বর্তমান আপলোড ও সাইটের মৌলিক ধারণা
2. কোন ফাইল কী করে
3. ছবি ও মিডিয়ার ফোল্ডার
4. GitHub-এর বাটন ও শব্দের অর্থ
5. পরিবর্তনের আগে ব্যাকআপ
6. GitHub থেকে `index.html` সম্পাদনা
7. নতুন ফাইল ও ফোল্ডার আপলোড
8. কোথায় কোন লেখা বদলাবেন: সম্পূর্ণ মানচিত্র
9. HTML-এর ছোট ছোট নিয়ম
10. নাম, পেশা, অবস্থান ও প্রধান সংখ্যা
11. নিজের পরিচয় ও জীবনের গল্প
12. থিসিস ও ফলাফল
13. নতুন প্রজেক্ট ও প্রজেক্টের লিংক
14. দক্ষতা, শিক্ষা, নেতৃত্ব ও পুরস্কার
15. প্রধান ও About Me ছবি বদলানো
16. নতুন ছবি ও ক্যাপশন যোগ করা
17. নতুন অ্যালবাম তৈরি ও ছবি সরানো
18. প্রজেক্টে ছবি যোগ করা
19. ভিডিও, YouTube ও captions
20. অডিও ও transcript
21. নিজের পেজে বাংলা–ইংরেজি আর্টিকেল
22. বাইরের আর্টিকেলের লিংক
23. CV, PDF ও অন্যান্য নথি
24. প্রোফাইল, ফোন, ইমেইল ও WhatsApp
25. মেনু ও নতুন অংশ
26. রং, ডার্ক মোড ও ফন্ট
27. সার্চের তথ্য ও সহায়ক ফাইল
28. Commit, deployment ও পরীক্ষা
29. সমস্যা হলে সমাধান
30. ভুল পরিবর্তন ফেরত নেওয়া
31. নিরাপত্তা, সীমা ও দৈনন্দিন চেকলিস্ট
32. বর্তমান ছবির পূর্ণ তালিকা

---


## v18: পুরো পোর্টফোলিওর visual polish / Full portfolio polish

- হালকা থিমে সোনালি ও ছোট লেখার রং গাঢ় করা হয়েছে; ডার্ক থিম অপরিবর্তিতভাবে পাঠযোগ্য।
- প্রধান ছবিতে নিজের archive-এর দিনের আলোতে suit portrait; Profile-এ waterside ছবি। ছবি AI দিয়ে বানানো বা আসল ছবি বদলানো হয়নি।
- Skills ও Recognition: desktop-এ ৩+২, tablet-এ ২+২+১ পূর্ণ-প্রস্থ, phone-এ এক কলাম; কোনো অর্জন বা দক্ষতা বানিয়ে যোগ করা হয়নি।
- প্রথম অংশের উচ্চতা কমানো হয়েছে; desktop-এ চারটি সংখ্যা একসঙ্গে দেখা যায়।
- মানচিত্রে জেলার সীমানা স্পষ্ট; district selector-এ পরিষ্কার তীর; কিবোর্ডের focus দৃশ্যমান।
- `EDIT: POLISH`, `EDIT: PHOTO PRESENTATION`, `EDIT: MAP CONTROLS`, `EDIT: TABLET / PHONE` দিয়ে নতুন নিয়ম খুঁজুন।

### Upload / GitHub-এ কী দেবেন
ডাউনলোড করা `index-v18.html`-এর নাম **index.html** করে আগের ফাইলটি replace করুন। আগের photos/, documents/, audio/, videos/ ফোল্ডার রেখে দিন; নতুন ছবি আপলোডের দরকার নেই। নতুন প্রধান ছবির পথ: `photos/travel/portraits/portrait.jpg`; দ্বিতীয় ছবি: `photos/travel/portraits/beyond-the-desk.jpg`। পুরোনো profile ছবিগুলো মুছবেন না।

### Verified / কী পরীক্ষা হয়েছে
Chromium-এ 320×740, 390×844, 820×1180, 1440×900 এবং 1920×1080 মাপে light ও dark—মোট ১০টি অবস্থায় পরীক্ষা হয়েছে। প্রতিটিতে সব ৬৪ district নির্বাচন, নির্বাচনের সঙ্গে map-এর মিল, next, keyboard Enter, খোলা/বন্ধ, photo viewer এবং ছোট পর্দার menu পরীক্ষা করা হয়েছে। অনুভূমিক overflow, ভাঙা লোড হওয়া ছবি বা JavaScript error পাওয়া যায়নি। Screenshot দেখে phone / tablet / desktop-এর বিন্যাসও পর্যালোচনা করা হয়েছে। বাস্তব iPhone, iPad, Mac বা Safari পরীক্ষা করা হয়নি; সব যন্ত্রে নিখুঁত বা “১০/১০” নিশ্চিত করার দাবি নয়।

English: This version improves contrast, reuses authentic brighter photographs, balances the existing five-item grids and makes district boundaries clearer. All 64 district selections were exercised in ten Chromium viewport/theme combinations. Real Apple hardware and Safari remain unverified. Rename index-v18.html to index.html for GitHub; keep all existing media folders.

## v17: ছোট ও খোলা/বন্ধ জেলা-অংশ / Compact collapsible atlas — 23 November 2026

Travel অংশের জেলা-মানচিত্র এখন শুরুতে বন্ধ থাকে। প্রথমে একটি ছোট কার্ড দেখায়: শিরোনাম, **64/64 districts · 8 divisions · 615 places** চিপ এবং ৬৪ ঘরের একটি সবুজ দাগ (সব জেলা ঘোরা হয়েছে বোঝাতে)। দর্শক চাইলে **Explore by district** চাপবেন—তখন মানচিত্র ও তালিকা খুলবে; **Hide districts** চাপলে আবার বন্ধ।

**English:** The district explorer now starts collapsed as a compact summary card (64/64 districts, 8 divisions, total places, a 64-cell progress strip). Visitors open it with **Explore by district** and close it with **Hide districts**. The map is smaller and places show in two columns on wide screens.

### কোথায় বদলাবেন / Where to edit

- শিরোনাম বা চিপের লেখা: Ctrl+F → `EDIT: ATLAS সারাংশ`
- ডিজাইন (মাপ, রং, কলাম): Ctrl+F → `EDIT: ATLAS v2`
- বোতামের কাজ: Ctrl+F → `EDIT: ATLAS TOGGLE`
- **615 places** সংখ্যা নিজে গোনা হয়—নতুন `<li>` যোগ করলে নিজেই বাড়বে। হাতে বদলাবেন না।
- `id="atlas-toggle"`, `id="atlas-body"`, `id="atlas-places"` মুছবেন না।

**English:** Edit text at `EDIT: ATLAS সারাংশ`, styling at `EDIT: ATLAS v2`, behaviour at `EDIT: ATLAS TOGGLE`. The places count is automatic. Keep the `atlas-*` ids.

### যা যাচাই হয়েছে / Checked

ফোন (390px), iPad (820px), Mac (1440px) ও PC (1920px)—চার মাপেই খোলা/বন্ধ, মানচিত্রে ক্লিক, ← → বোতাম ও dropdown কাজ করে; পাশে স্ক্রল হয় না; কোনো JavaScript ত্রুটি নেই। আসল iPhone/iPad/Safari-তে আলাদাভাবে পরীক্ষা করা হয়নি; আপলোডের পর নিজের ফোনে একবার দেখে নিন।

**English:** Tested at 390, 820, 1440 and 1920px (Chromium): toggle, map, arrows and dropdown work, no horizontal scroll, no errors. Not tested on physical Apple devices/Safari.

### GitHub-এ আপলোড / Upload

শুধু নতুন `index.html` দিয়ে পুরোনোটি বদলান (Add file → Upload files → `index.html` → Commit changes)। ছবি বা অন্য ফোল্ডার বদলানোর দরকার নেই।

**English:** Replace only `index.html` in your repository. No photo or folder changes are needed.

## v16 চূড়ান্ত সংস্করণ / Final release — 23 November 2026

**সবচেয়ে আগে:** `obaeedma-github-pages_v16.zip` Extract করুন। ভেতরের `index.html`, `photos/`, অন্যান্য ফোল্ডার ও সহায়ক ফাইল GitHub রিপোজিটরির মূল জায়গায় দিন। বাইরের `obaeedma-v16` ফোল্ডার বা ZIP নিজে আপলোড করবেন না। GitHub Actions সফল হলে সাইটে Ctrl+F5 দিন। আগে নিজের বর্তমান সাইটের ব্যাকআপ রাখুন; নিজের পরে যোগ করা ছবি/ভিডিও মুছবেন না।

**English:** Extract the release ZIP. Upload its contents to the repository root, not a surrounding folder or the ZIP itself. Keep a backup and retain any media you added independently. After successful Pages deployment, hard-refresh.

**আলাদা কোড:** `index_v16.html` একই সম্পূর্ণ কোড; GitHub-এ দেওয়ার আগে নাম `index.html` করুন। ফাইলটি একা ছবি বহন করে না; সম্পূর্ণ ZIP-এর `photos/`-ও প্রয়োজন। পুরনো root `index.html` অবশ্যই Replace করবেন।

**পরিচয়ের সংশোধন:** Data Analytics ও Leadership একসঙ্গে; OfficeKhoj BD = Software; ReWater = Website; নেতৃত্বের Team Lead চিহ্ন অক্ষত। ভবিষ্যৎ ব্যবসা/management-এর আগ্রহকে অর্জিত পদ বা যোগ্যতা বানানো হয়নি।

**English:** OfficeKhoj BD is software, ReWater is a website; analytics and leadership remain highlighted. Future ambitions are not presented as completed qualifications.

**যা যাচাই হয়েছে:** ৬৪ জেলার সব ৬১৫ এন্ট্রি মূল তালিকার সঙ্গে মেলে; সব জেলা-সীমানা একই স্লাইড নির্বাচন করে; 360, 390, 822 ও 1280px পর্দায় ছবি, অ্যালবাম, মেনু ও dark/light কাজ করে। JavaScript বন্ধ থাকলেও পুরো স্থানতালিকা থাকে। প্রস্তুত ZIP-এর স্থানীয় ছবি ও সম্পূর্ণ ফাইলও পরীক্ষা করা হয়েছে। বাইরের সব profile link-এর বর্তমান account/content বা আপনার GitHub-এ ভবিষ্যৎ deployment এই পরীক্ষা নিশ্চিত করে না।

**English:** Local and exported-page checks cover district data, map selection, mobile/desktop, themes and photo viewing. They do not certify external account content, every landmark's current access status or a future GitHub deployment.

## v16: জেলার সব স্থান ও মানচিত্র / Complete district atlas

আপনার দেওয়া ৬৪ জেলার ৬১৫টি তালিকার এন্ট্রি অক্ষত আছে। কোনো এন্ট্রিতে একাধিক স্থানের নাম একসঙ্গে থাকলে সেভাবেই রাখা হয়েছে। এগুলো সব স্থানে আপনার যাওয়ার আলাদা দাবি নয়; জেলার দর্শনীয় তালিকা।

**English:** All 615 supplied list entries across 64 districts are preserved, including grouped names. The landmark catalogue is not a claim that every listed site was personally visited.

- জেলার সবুজ চিহ্ন, বাংলাদেশের মানচিত্রের জেলা বা District তালিকা—তিনটি থেকেই একই স্লাইড খুলবে।
- নিচের ← ও → দিয়ে আগের/পরের জেলা; শেষ জেলা থেকে আবার প্রথমটি। তালিকার ভেতরে নিচে স্ক্রল করলে বাকি সব নাম দেখবেন।
- মোবাইলে স্লাইডে অনুভূমিক swipe; কীবোর্ডে মানচিত্রে Tab তারপর Enter/Space। স্লাইডে ফোকাস দিয়ে ← / → চাপুন।
- **English:** Select via map, markers or dropdown. Arrows cycle districts; scroll within the list to read every place. Swipe horizontally on mobile. Tab and Enter/Space select a map district.

### স্থান যোগ/সরানো / Add or remove places

GitHub → `index.html` → Edit → Ctrl+F → `EDIT: DISTRICT Narayanganj` (বা আপনার জেলার নাম)। সংশ্লিষ্ট `<ol class="district-places">`-এ প্রতিটি স্থান আলাদা `<li>`।

```html
<li>Panam Nagar</li>
<li>Sonargaon Folk Arts and Crafts Museum</li>
<li>আপনার নতুন দর্শনীয় স্থানের নাম</li>
```

নাম মুছতে শুধু পুরো `<li>…</li>` লাইন সরান। সংখ্যা নিজে বদলাবে; JavaScript বা আলাদা তালিকা সম্পাদনা লাগবে না। `&` লিখতে `&amp;` দিন। জেলা নাম, `data-district`, `data-division`, `id`, SVG `path d` মুছবেন বা বদলাবেন না।

**English:** Edit only the relevant district's `<li>` entries. Counts update automatically. Do not edit district identifiers or map path geometry. Map boundaries are embedded, so no API key, map account or extra download is needed.

### মানচিত্রের উৎস / Map attribution

geoBoundaries gbOpen BGD ADM2; উৎস Bangladesh Bureau of Statistics / OCHA ROAP; license CC BY 3.0 IGO। মানচিত্রের নিচের attribution ও license link রাখবেন। এটি প্রশাসনিক সীমানার চিত্র, যাতায়াত নির্দেশনা নয়।


---

## ১. বর্তমান আপলোড / Your current upload

আপনার দেওয়া স্ক্রিনশটে `index.html`, `photos`, `audio`, `videos`, `documents` সরাসরি রিপোজিটরির মূল তালিকায় আছে—এটাই সঠিক বিন্যাস। স্ক্রিনশটে deployment-এর পাশে হলুদ চিহ্ন দেখা যাচ্ছে; সেটি শেষ হওয়ার প্রমাণ নয়। সর্বশেষ deployment সফল হয়েছে কি না **Actions**-এ দেখবেন।

- মূল ঠিকানা: `https://obaeedma.github.io/`
- ফাইলের মূল জায়গা বা **root**: GitHub-এ `obaeedma / obaeedma.github.io` খুললে প্রথম যে তালিকা আসে।
- `index.html` হলো পুরো পোর্টফোলিও: লেখা, ডিজাইন এবং মেনু/ছবি দেখার নিয়ম এতে আছে।
- ছবি, ভিডিও, অডিও ও PDF আলাদা ফোল্ডারে থাকে; `index.html` তাদের ঠিকানা উল্লেখ করে।
- কোনো সফটওয়্যার ইনস্টল, build বা terminal command চালানো ছাড়াই GitHub-এর ব্রাউজার দিয়ে সম্পাদনা সম্ভব।
- দর্শক আপনার সাইটে ফাইল আপলোড করতে পারবে না। মালিক হিসেবে আপনি GitHub থেকে ফাইল ও কোড বদলাবেন।

**English:** Your screenshot shows the correct root-level layout. GitHub Pages serves `index.html`; it loads media from neighbouring folders. A yellow deployment indicator does not prove deployment has finished. This is an owner-edited static site, not a visitor upload portal.

### সবচেয়ে গুরুত্বপূর্ণ সতর্কতা

**পুরো বাইরের `obaeedma-final-upload` ফোল্ডারটি আবার আপলোড করবেন না।** তার ভেতরের `index.html`, `photos/` ইত্যাদি মূল তালিকায় দিতে হবে। বাইরে আরেকটি ফোল্ডার দিলে নতুন সাইট মূল ঠিকানার বদলে সাব-ঠিকানায় চলে যাবে। ZIP নিজে আপলোড করলেও তার ভেতরের সাইট স্বয়ংক্রিয়ভাবে বের হয় না।

**English:** Upload the package’s contents, not its outer folder and not the ZIP itself.

---

## ২. কোন ফাইল কী করে / File-by-file explanation

| ফাইল বা ফোল্ডার | বাংলা: কাজ ও করণীয় | English |
|---|---|---|
| `index.html` | পুরো সাইটের মূল ফাইল। লেখা, ছবি দেখানোর ঠিকানা, রং ও কাজ করার নিয়ম এতে। | Main page: content, styles and interactions. |
| `photos/` | আসল ছবিগুলো। শুধু HTML দিলে ছবি আসবে না। | Actual photographs; upload alongside HTML. |
| `videos/` | নিজের MP4 ও `.vtt` captions রাখুন। | Video files and captions. |
| `audio/` | নিজের MP3 বা অন্য সমর্থিত অডিও। | Audio files. |
| `documents/` | প্রকাশ্য CV, PDF, গবেষণা নথি। | Public CVs and PDFs. |
| `EDITING-GUIDE.md` | আগের সংক্ষিপ্ত সম্পাদনা গাইড। এটি মুছলে সাইট নষ্ট হবে না, তবে রাখা ভালো। | Existing short editing guide. |
| `PHOTO-INDEX.csv` | আগের ছবির নাম, নতুন পথ ও ক্যাপশন মিলিয়ে দেখার তালিকা। Excel-এ খুলতে পারবেন। এটি সাইট চালায় না। | Reference inventory, not a runtime photo database. |
| `robots.txt` | সার্চ ইঞ্জিনকে crawling-এর নির্দেশ ও sitemap-এর ঠিকানা দেয়। | Search crawler guidance. |
| `sitemap.xml` | সার্চ ইঞ্জিনের জন্য পেজের ঠিকানার তালিকা। | Search engine page inventory. |
| `google05d55b660994bbbd.html` | Google Search Console-এর মালিকানা যাচাইয়ের ফাইল। নাম/ভেতরের লেখা বদলাবেন না। | Google ownership verification; leave unchanged. |
| `.nojekyll` | GitHub Pages-কে সরাসরি স্থির ফাইল পরিবেশন করতে সহায়তা করে। প্যাকেজে আছে; Windows-এ দেখতে বাদ পড়তে পারে। | Static delivery marker; keep it if supplied. |
| মিডিয়া ফোল্ডারের `README.txt` | ফোল্ডারের ব্যবহার বোঝায়; placeholder ছবি/ভিডিও নয়। | Notes, not playable media. |
| এই নির্দেশিকা | বিস্তারিত সাহায্য। সাইটের মেনুতে নিজে থেকে দেখা যাবে না। | Your maintenance handbook. |

**স্ক্রিনশটে `.nojekyll` দেখা যাচ্ছে না বলে সেটি আছে ধরে নেবেন না।** রিপোজিটরিতে খুঁজুন; না থাকলে root-এ Add file → Create new file দিয়ে `.nojekyll` নামে একটি ফাইল রাখতে পারেন। কোনো লেখা প্রয়োজন নেই। আপনার বর্তমান সাইট ঠিক চললে শুধু এই কারণে অন্য সেটিংস বদলানোর দরকার নেই।

---

## ৩. ফোল্ডার বিন্যাস / Folder structure

```text
obaeedma.github.io/                 ← মূল জায়গা / root
├── index.html
├── photos/
│   ├── profile/                    ← প্রধান ও About Me ছবি
│   ├── leadership/                 ← নেতৃত্বের গ্রুপ ছবি
│   ├── projects/
│   │   ├── robot-car-automated-crane/
│   │   └── water-gas-safety-prototype/
│   └── travel/
│       ├── featured/               ← প্রথমে দেখা ৮টি ভ্রমণের ছবি
│       ├── hills-light/
│       ├── sea-lakes/
│       ├── trails-friends/
│       ├── portraits/
│       └── campus/
├── videos/
├── audio/
├── documents/
├── EDITING-GUIDE.md
├── PHOTO-INDEX.csv
├── robots.txt
├── sitemap.xml
├── google05d55b660994bbbd.html
└── .nojekyll
```

নতুন প্রজেক্ট: `photos/projects/my-new-project/`  
নতুন ভ্রমণ: `photos/travel/my-new-trip/`  
অনেক ভিডিও হলে: `videos/my-new-project/demo.mp4`

সব উদাহরণের `my-new-project`, `my-new-trip`, শিরোনাম ও বর্ণনা **নমুনা**, আপনার বাস্তব তথ্য নয়। প্রকাশের আগে নিজের নাম/লেখা দিন।

**English:** Use topic-based subfolders. Example names and text in this guide are placeholders, not claims about your work.

---

## ৪. GitHub-এর শব্দ / GitHub vocabulary

| যা দেখবেন | সহজ অর্থ / Meaning |
|---|---|
| **Code** tab | ফাইলের তালিকা / Repository files. |
| **main** | আপনার বর্তমান মূল branch / Current main branch. |
| **Add file → Upload files** | ছবি, ভিডিও, HTML ইত্যাদি আপলোড / Upload files. |
| **Add file → Create new file** | নতুন text/code file তৈরি / Create a text file. |
| **Edit / পেন্সিল চিহ্ন** | ফাইলের লেখা বদলানো / Edit a file. |
| **Preview** | Markdown হলে লেখা কেমন দেখায়; `index.html`-এর সম্পূর্ণ সাইট preview নয়। |
| **Commit changes** | পরিবর্তন রিপোজিটরিতে সংরক্ষণ / Save a revision. |
| **Commit message** | কী বদলেছেন তার ছোট নোট / Short description of your change. |
| **Actions** | ওয়েবসাইট প্রকাশের অগ্রগতি / Deployment progress. |
| **History** | ফাইলের আগের সংস্করণ / Previous revisions. |
| **Settings → Pages** | GitHub Pages-এর প্রকাশের সেটিংস / Website publishing settings. |
| **Raw / Download raw file** | ফাইলের আসল লেখা দেখা বা ডাউনলোড / Raw file contents. |

GitHub-এর বাটনের অবস্থান বা নাম সময়ে বদলাতে পারে। পেন্সিল না দেখলে ফাইলের ওপরে `…` মেনু দেখুন। নিজের সঠিক GitHub অ্যাকাউন্টে sign in থাকলে সম্পাদনা করতে পারবেন।

---

## ৫. পরিবর্তনের আগে ব্যাকআপ / Back up first

1. রিপোজিটরির মূল তালিকায় যান।
2. সবুজ **Code → Download ZIP** চাপুন।
3. কম্পিউটারে নাম দিন, যেমন `portfolio-backup-2026-11-23.zip`।
4. বড় পরিবর্তনের আগে নতুন ব্যাকআপ নিন।
5. নতুন ছবি/ভিডিওর আসল কপিও নিজের কাছে রাখুন।

ছোট লেখা বদলানোর আগে শুধু `index.html`-এর raw copy ডাউনলোড রাখলেও উপকার হবে। পুরনো HTML ও পুরনো ছবির ফোল্ডার একই ব্যাকআপে রাখা সবচেয়ে নিরাপদ।

**English:** Download a repository ZIP before major edits. Keep HTML and its matching media together. Git history is useful, but a local backup is simpler for recovery.

---

## ৬. `index.html` সম্পাদনা / Edit the main page

### ব্রাউজার দিয়ে / In your browser

1. https://github.com/obaeedma/obaeedma.github.io খুলুন।
2. `index.html` ক্লিক করুন।
3. পেন্সিল / **Edit this file** চাপুন।
4. সম্পাদনার লেখার ভেতরে ক্লিক করুন। **Ctrl+F** দিয়ে নিচের মানচিত্রের শব্দ খুঁজুন। ব্রাউজারের খোঁজ কাজ না করলে editor-এর Find ব্যবহার করুন।
5. শুধু প্রয়োজনীয় লেখা বা ছোট অংশ বদলান।
6. **Commit changes…** চাপুন।
7. message দিন, যেমন `Update About Me introduction`।
8. নিজের রিপোজিটরিতে সাধারণ পরিবর্তনে **Commit directly to the main branch** বেছে নিতে পারেন।
9. আবার **Commit changes** চাপুন।
10. **Actions**-এ শেষ প্রকাশ সফল হওয়া দেখুন; তারপর লাইভ সাইট পরীক্ষা করুন।

**সতর্কতা:** স্ক্রিনে শুধু লেখা বদলালেই save হয় না—Commit করতে হবে। `EDIT:` খুঁজলে CSS-এর মন্তব্যও পাওয়া যায়। লেখার জন্য নিচের `id="..."` খুঁজলে সঠিক content অংশে পৌঁছানো সহজ।

### কম্পিউটারে সম্পাদনা / Optional local editing

- ডাউনলোড করা `index.html` VS Code বা Notepad-এ খুলুন।
- UTF-8 হিসেবে save করুন; ফাইলের নাম অবশ্যই `index.html`, `index.html.txt` নয়।
- Windows File Explorer → View → Show → **File name extensions** চালু করুন।
- পাশেই matching `photos/` রেখে `index.html` ডাবল-ক্লিক করে প্রাথমিক পরীক্ষা করতে পারেন।
- অনলাইন fonts বা media captions-এর কিছু আচরণ local file-এ আলাদা হতে পারে; শেষ পরীক্ষা লাইভ সাইটে করুন।
- পরিবর্তিত `index.html` রিপোজিটরির root-এ Upload files দিয়ে দিন।

**English:** Edit the root `index.html`, commit, wait for deployment and test the live website. Local editing is optional; preserve UTF-8 and the `.html` extension.

---

## ৭. নতুন ফাইল আপলোড / Upload media and create folders

### আগে থেকেই থাকা ফোল্ডারে

ধরুন নতুন ভ্রমণের ছবি hills-light অ্যালবামে দিতে চান:

1. GitHub-এ `photos` → `travel` → `hills-light` খুলুন।
2. **Add file → Upload files** চাপুন।
3. পিসি থেকে `new-hill-photo.jpg` দিন।
4. Commit করুন।
5. এখন `index.html`-এ `photos/travel/hills-light/new-hill-photo.jpg` ব্যবহার করুন।

**একটি ছবি ফাইল আপলোড করলেই gallery-তে নিজে থেকে যোগ হয় না।** নতুন ছবির HTML অংশও যোগ করতে হবে। একই পুরনো নাম দিয়ে replace করলে সাধারণত HTML বদলাতে হয় না।

### নতুন ফোল্ডার দরকার হলে

GitHub-এ আলাদা “Create folder” বাটন সাধারণত নেই। দুইটি সহজ উপায়:

**উপায় A — কম্পিউটার থেকে:**
1. পিসিতে `photos/travel/my-new-trip/` বিন্যাসে ছবি রাখুন।
2. রিপোজিটরির root-এর Upload files পেজে `photos` ফোল্ডারটি টেনে দিন।
3. আপলোড তালিকায় পথ `photos/travel/my-new-trip/photo-01.jpg` হচ্ছে কি না দেখুন।
4. `photos/photos/...` বা `obaeedma-final-upload/photos/...` হলে বাতিল করে সঠিক জায়গা থেকে দিন।

**উপায় B — GitHub-এ:**
1. রিপোজিটরির root → Add file → Create new file।
2. নামের ঘরে `photos/travel/my-new-trip/README.txt` লিখুন।
3. ভেতরে অ্যালবামের একটি ছোট নোট লিখে Commit করুন।
4. নতুন ফোল্ডার খুলে Upload files দিয়ে ছবি দিন।

Git খালি ফোল্ডার সংরক্ষণ করে না; অন্তত একটি ফাইল থাকলে ফোল্ডার থাকবে।

### ফাইলের নাম / Naming rules

- ছোট ইংরেজি অক্ষর ও হাইফেন: `hill-sunrise.jpg` ভালো।
- স্পেস, অপ্রয়োজনীয় punctuation ও খুব বড় নাম এড়ান।
- `Photo.JPG` আর `photo.jpg` এক নাম নয়—GitHub Pages-এ case মিলতে হবে।
- JPG-কে শুধু rename করে PNG/MP4 বানাবেন না; সত্যিকারের format-এ export করুন।
- কোডে `/` ব্যবহার করুন; Windows-এর `\` নয়।
- `C:\Photos\my-photo.jpg` সাইটের ঠিকানা নয়।
- root-এর `index.html` থেকে `photos/...` লিখুন; এখানে `../` দরকার নেই।

**English:** Upload media first, then reference its exact repository-relative path in HTML. Folder placement and letter case matter. Uploading a new file does not automatically create a gallery item.

---

## ৮. কোথায় কী বদলাবেন / Complete editing map

`index.html`-এ নিচের search text খুঁজুন। Line number ব্যবহার না করাই ভালো—নতুন content যোগ হলে নম্বর বদলে যায়।

| পরিবর্তন / Change | খুঁজবেন / Search | ভেতরে যা বদলাবেন |
|---|---|---|
| ওপরের logo/name ও menu | `EDIT: মেনু —` | brand-এর লেখা, menu-এর link |
| মূল নাম, পেশা, অবস্থান | `id="top"` | `h1`, `status`, `role` |
| প্রধান ছবি | `photos/travel/portraits/portrait.jpg` | `src`, `alt`, `figcaption` |
| মূল সংখ্যাগুলো | `EDIT: সংখ্যা` | `data-c`, `data-suffix`, দৃশ্যমান সংখ্যা |
| About Me | `id="profile"` | `prose`-এর `p`, `facts`-এর `li` |
| দ্বিতীয় ছবি | `photos/travel/portraits/beyond-the-desk.jpg` | `src`, `alt`, caption |
| জীবনের গল্প | `id="journey"` | `ol class="story"`-এর `li` |
| থিসিস | `id="thesis"` | title, description, methods, results |
| প্রজেক্ট | `id="projects"` | `article class="proj..."` |
| Robot Car | `Robot Car` | ওই article-এর লেখা ও `bench-photos` |
| Water & Gas | `Water &amp; Gas` | ওই article-এর লেখা ও ছবি |
| দক্ষতা | `id="skills"` | group heading ও `span class="chip"` |
| শিক্ষা | `id="education"` | `ol class="tl rv"`-এর `li` |
| নেতৃত্ব | `id="leadership"` | `div class="row rv"` |
| পুরস্কার | `id="achievements"` | `div class="aw rv"`, Full honours list |
| ভ্রমণের লেখা/featured ছবি | `id="travel"` | paragraph, প্রথম gallery |
| ছোট অ্যালবাম | `class="album"` | summary ও ভেতরের gallery |
| নিজের লেখা/মিডিয়া/PDF | `id="publications"` | এই div-এর ভেতরে নতুন content |
| উদাহরণগুলো | `FUTURE CONTENT`, `PHOTO TEMPLATE` | comment-এর ভেতর থেকে উদাহরণ কপি |
| ৮টি profile link | `EDIT: GitHub`, `EDIT: Kaggle` ইত্যাদি | `href`, নাম, ছোট বর্ণনা |
| ফোন ও ইমেইল | `id="contact"` | দৃশ্যমান লেখা এবং `href` দুটো |
| footer | `EDIT: পেজের শেষ অংশ` | নাম, অবস্থান; বছর নিজে আপডেট হয় |
| search title/description | `EDIT: SEO` | `title`, description, social metadata |
| পরিচয়ের JSON | `EDIT: পরিচয়` | নাম, phone, email, `sameAs` |
| বর্তমান রং | `:root {` | CSS color variables |
| dark palette | `EDIT: DARK MODE` | dark theme variables |

**English:** Search by section ID or editing comment, not by line number. Repeated elements should be copied as complete blocks.

---

## ৯. HTML-এর ছোট নিয়ম / Essential HTML rules

```html
<h3>শিরোনাম / Heading</h3>
<p>একটি অনুচ্ছেদ / A paragraph.</p>
<p>আরেকটি অনুচ্ছেদ / Another paragraph.</p>
<strong>গুরুত্বপূর্ণ লেখা / Important words</strong>
<em>জোর দেওয়া লেখা / Emphasis</em>
<a href="https://example.com" target="_blank" rel="noopener">Open website ↗</a>
```

- `<p>` শুরু, `</p>` শেষ। মাঝের লেখা বদলানো সবচেয়ে নিরাপদ।
- `<div>`, `<section>`, `<article>`, `<figure>`-এর শুরু ও শেষ দুটোই রাখুন।
- `<img>`-এর আলাদা `</img>` নেই।
- `class="..."` হলো ডিজাইনের পরিচয়। অকারণে মুছবেন না।
- `id="..."` হলো অংশের ঠিকানা। একই id দুইবার দেবেন না।
- `href` হলো ক্লিক করলে কোথায় যাবে। `src` হলো কোন ফাইল দেখাবে।
- `alt` হলো ছবি না এলে বা screen reader-এ শোনা ছবির বর্ণনা।
- `figcaption` হলো দৃশ্যমান ছবির caption।
- HTML-এ `&` লিখতে `&amp;`, `<` লিখতে `&lt;`, `>` লিখতে `&gt;` দিন।
- attribute-এর মধ্যে double quote লিখতে `&quot;` ব্যবহার করুন।
- URL-এ `&` থাকলে HTML source-এ `&amp;` রাখুন।
- ইংরেজি code quote `"` ব্যবহার করুন; বাঁকানো smart quotes `“ ”` দিয়ে attribute বানাবেন না।
- বাংলা লেখা UTF-8-এ রাখুন।

### Comment আর দৃশ্যমান content আলাদা

```html
<!-- এটি শুধু নির্দেশনা; দর্শক দেখবে না। -->
<p>এই লেখাটি দর্শক দেখবে।</p>
```

বর্তমান template-গুলো বড় `<!-- ... -->` comment-এর ভেতরে আছে। **শুধু প্রয়োজনীয় HTML কপি করে comment-এর বাইরে সঠিক স্থানে বসাবেন।** বড় comment-এর ভেতরে নতুন content রেখে দিলে সেটি লুকিয়ে থাকবে। এক comment-এর ভেতরে আরেক comment ঢোকাবেন না।

**English:** Preserve tags, classes and unique IDs. Comments are invisible. Copy usable template markup outside the surrounding comment.

---

## ১০. প্রধান নাম, পরিচয় ও সংখ্যা / Hero and metrics

`id="top"` খুঁজুন। বর্তমান নামের গঠন:

```html
<h1><span class="ini">M A</span><em>Obaeed</em></h1>
```

এভাবে M A ওপরের লাইনে, Obaeed নিচের লাইনে থাকে। নামের line layout রাখতে `span` ও `em` মুছবেন না।

- `class="status"`: Dhaka, Bangladesh এবং কাজের availability-এর লেখা।
- `class="role"`: Data Analyst পরিচয় ও supporting paragraph।
- `class="btns"`: View work, Read the thesis, Get in touch link।

### সংখ্যা বদলানোর উদাহরণ

```html
<div>
  <b data-c="25" data-suffix="+">25+</b>
  <span>Academic &amp; independent projects</span>
</div>
```

প্রকৃত সংখ্যা ভবিষ্যতে বদলালে `data-c="25"` **ও** মাঝের `25+` দুটো মিলিয়ে বদলান। `+` রাখতে `data-suffix="+"` থাকে; নির্দিষ্ট সংখ্যা হলে suffix বাদ দিতে পারেন। শুধু এই গাইড পড়ে সংখ্যা বাড়াবেন না—নিজের যাচাইকৃত তথ্য ব্যবহার করুন। JavaScript বন্ধ থাকলেও মাঝের সংখ্যাটি দেখা যায়।

**English:** Update both animated numeric data and visible fallback text. Keep the existing two-line name structure and use verified figures only.

---

## ১১. About Me ও My Journey / Biography and story

### পরিচয়ে নতুন paragraph

`id="profile"` → `<div class="prose rv">` খুঁজুন। পুরনো paragraph-এর পরে, একই div-এর ভেতরে দিন:

```html
<p lang="bn">এখানে নিজের নতুন পরিচয়ের অনুচ্ছেদ লিখুন।</p>
<p lang="en">Write your new English introduction here.</p>
```

এগুলো নমুনা; প্রকাশের আগে বাস্তব লেখা দিন। বাংলার জন্য `lang="bn"`, ইংরেজির জন্য `lang="en"` ভালো।

Facts তালিকায় নতুন তথ্য:

```html
<li><span>Focus</span><span>আপনার যাচাইকৃত বর্তমান কাজের বিষয়</span></li>
```

এটি `ul class="facts"`-এর ভেতরে বসান।

### জীবনের নতুন ধাপ

`id="journey"` → `ol class="story"`-এর ভেতরে একটি সম্পূর্ণ `li` যোগ করুন:

```html
<li class="rv">
  <span class="yr">আপনার বছর / Your year</span>
  <h3>নতুন ধাপের শিরোনাম / Milestone title</h3>
  <p>বাস্তব অভিজ্ঞতার ছোট বর্ণনা লিখুন।</p>
</li>
```

**English:** Add paragraphs inside the profile prose container; add milestones as complete list items inside the journey list.

---

## ১২. থিসিস / Thesis updates

`id="thesis"` খুঁজুন। সেখানে শিরোনাম, BIDWESH dataset-এর কথা, ব্যাখ্যা, পদ্ধতি, মডেল ও ফলাফলের উপস্থাপনা আছে।

- শিরোনাম বদলাতে ওই অংশের `h2`-এর মাঝের লেখা বদলান।
- বর্ণনা বদলাতে তার নিচের paragraph-গুলো বদলান।
- ফলাফল বদলালে prose ও ফলাফল দেখানো অন্য লেখাও মিলিয়ে বদলান।
- model label, accuracy, macro-F1 ইত্যাদি শুধু নতুন যাচাইকৃত গবেষণার ফল অনুযায়ী বদলাবেন।
- chart-এর উচ্চতা/প্রস্থ/শতাংশসহ styling না বুঝে বদলাবেন না; মান পাল্টালে chart ও লেখা পরস্পরের সঙ্গে মিলতে হবে।
- পূর্ণ thesis PDF প্রকাশ করতে §২৩-এর link এই thesis অংশের উপযুক্ত paragraph-এর পরেও বসাতে পারবেন।
- সহলেখক বা অন্যের তথ্য প্রকাশের আগে অনুমতি ও সঠিক attribution রাখুন।

**English:** Keep research claims, model labels, chart values and prose consistent. A thesis PDF link can be placed directly in the thesis section.

---

## ১৩. নতুন প্রজেক্ট / Add a project

`id="projects"` → `<div class="projects">` খুঁজুন। নতুন card ওই div-এর ভেতরে, বিদ্যমান article-এর পরে কিন্তু বাইরের closing `</div>`-এর আগে দিন।

```html
<article class="proj rv">
  <span class="tag">আপনার প্রকৃত বিভাগ / Actual category</span>
  <h3>আপনার প্রজেক্টের নাম / Project title</h3>
  <dl>
    <dt>Question</dt>
    <dd>কোন সমস্যা সমাধান করেছেন বা কোন প্রশ্ন পরীক্ষা করেছেন?</dd>
    <dt>What I did</dt>
    <dd>নিজে কী কাজ করেছেন, কী পদ্ধতি ব্যবহার করেছেন?</dd>
    <dt>Outcome</dt>
    <dd>যাচাই করা ফলাফল ও সীমাবদ্ধতা লিখুন।</dd>
  </dl>
  <div class="stack">
    <span class="chip">প্রকৃত ব্যবহৃত দক্ষতা</span>
    <span class="chip">আরেকটি প্রকৃত দক্ষতা</span>
  </div>
  <p>
    <a href="https://github.com/YOUR-USERNAME/YOUR-REPOSITORY"
       target="_blank" rel="noopener">View code ↗</a>
  </p>
</article>
```

**এই URL নমুনা—নিজের সত্যিকারের repository URL দিয়ে বদলাবেন; link না থাকলে পুরো link paragraph বাদ দিন।** আইকন না দিলেও এই ছোট card চলবে। একই রকম icon/layout চাইলে কাছাকাছি পুরনো article সম্পূর্ণ কপি করে তার তথ্য বদলান; SVG-এর ভেতরের path না বুঝে বদলাবেন না।

দলের কাজ হলে নিজের অবদান স্পষ্ট করুন। course code বা ফলাফল না থাকলে বানিয়ে যোগ করবেন না। নতুন card-এর ভেতরে ছবি বা ভিডিও দিতে §১৮–১৯ অনুসরণ করুন।

**English:** Insert a complete article inside `.projects`. Describe the actual question, personal contribution and verified outcome. Replace sample URLs or remove unavailable links.

---

## ১৪. দক্ষতা, শিক্ষা, নেতৃত্ব ও পুরস্কার / Lists

### দক্ষতা / Skills

`id="skills"` খুঁজে সংশ্লিষ্ট দলের chip-গুলোর পাশে দিন:

```html
<span class="chip">Your verified skill</span>
```

একটি নতুন group চাইলে বিদ্যমান skill group সম্পূর্ণ কপি করে heading ও chips বদলান।

### শিক্ষা / Education

`id="education"` → `ol class="tl rv"`-এর ভেতরে:

```html
<li>
  <span class="yr">সম্পন্ন করার বছর / Year</span>
  <h3>ডিগ্রি বা কোর্সের প্রকৃত নাম</h3>
  <p>প্রতিষ্ঠান, স্থান এবং প্রাসঙ্গিক প্রকৃত তথ্য।</p>
</li>
```

বর্তমান নকশায় GPA দেখানো হয় না।

### নেতৃত্ব / Leadership

`id="leadership"`-এর বিদ্যমান row-গুলোর একই parent-এর ভেতরে:

```html
<div class="row rv">
  <h3>প্রতিষ্ঠান / Organisation</h3>
  <span class="r">পদ / Actual role</span>
  <p>আপনার দায়িত্ব ও বাস্তব কাজের বর্ণনা।</p>
</div>
```

### পুরস্কার / Awards

`id="achievements"`-এর পুরস্কার grid-এ:

```html
<div class="aw rv">
  <b>প্রকৃত ফলাফল <small>সাল</small></b>
  <h3>পুরস্কার বা প্রতিযোগিতার প্রকৃত নাম</h3>
</div>
```

শুধু লম্বা তালিকায় যোগ করতে **Full honours list** খুঁজুন; তার `ul`-এর ভেতরে একটি `li` যোগ করুন। বাইরে আলাদা ভুল জায়গায় বসাবেন না।

**English:** Copy a full existing item into its matching container. Add only genuine skills, education, roles and awards.

---

## ১৫. প্রধান ও দ্বিতীয় ছবি / Replace portraits

### প্রধান ছবি / Main portrait

বর্তমান পথ: `photos/travel/portraits/portrait.jpg`

সবচেয়ে সহজ:
1. নিজের নতুন ছবিকে সত্যিকারের JPEG হিসেবে export করুন।
2. নাম দিন `portrait.jpg`।
3. GitHub-এ `photos/profile` খুলে Upload files দিয়ে দিন।
4. একই নামের ফাইল replace করার পরিবর্তন দেখে Commit করুন।
5. ছবির বিষয় বদলালে `index.html`-এ ওই ছবির `alt` ও caption মিলিয়ে দিন।

### About Me ছবি

একই পদ্ধতি; নাম `beyond-the-desk.jpg`, পথ `photos/travel/portraits/beyond-the-desk.jpg`।

### অন্য নাম ব্যবহার করলে

`index.html`-এ ছবির `src` নতুন পথ দিন। প্রধান দুই ছবির বর্তমান markup-এ gallery-এর মতো `data-photo` link নেই; তাই সেখানে না থাকা `href` খুঁজে বদলানোর দরকার নেই। Gallery/project ছবিতে `href` ও `src` দুটোই বদলাতে হয়।

### ছবির বাস্তব width/height

প্রধান ছবিতে `width="1200" height="1600"`; দ্বিতীয় ছবিতে `width="1600" height="1204"` আছে। নতুন ছবির অনুপাত ভিন্ন হলে নিজের ফাইলের প্রকৃত pixel dimensions বসান। Windows-এ Right-click → Properties → Details-এ dimensions দেখতে পারবেন। এগুলো ছবির মাপের তথ্য, ফাইলের KB নয়।

বর্তমান নকশা সম্পূর্ণ ছবি দেখায়; অকারণে `object-fit: cover` বা নির্দিষ্ট ছোট height বসালে আবার কাটতে পারে।

**English:** Replacing the same filename avoids path edits. Update descriptions and real image dimensions if the image changes. Preserve the uncropped photo styling.

---

## ১৬. নতুন ছবি / Add a gallery photograph

### ধাপে ধাপে উদাহরণ

ধরুন hills-light অ্যালবামে `new-hill-photo.jpg` দেবেন:

1. ফাইল আপলোড: `photos/travel/hills-light/new-hill-photo.jpg`।
2. root-এর `index.html` Edit করুন।
3. `Hills &amp; light` খুঁজুন।
4. ওই `<details class="album">`-এর ভেতরের `<div class="gallery">` দেখুন।
5. পুরনো একটি সম্পূর্ণ `<figure ...>...</figure>`-এর পরে, **gallery-এর closing `</div>`-এর আগে** নিচের অংশ দিন।
6. নিজের বর্ণনা ও caption লিখে Commit করুন।

```html
<figure class="g-item">
  <a href="photos/travel/hills-light/new-hill-photo.jpg"
     data-photo="" aria-label="View hill photograph">
    <img src="photos/travel/hills-light/new-hill-photo.jpg"
         alt="নিজের ছবিতে কী দেখা যাচ্ছে তার সঠিক বর্ণনা"
         loading="lazy" />
    <figcaption>নিজের ছবির ছোট নাম ↗</figcaption>
  </a>
</figure>
```

### প্রতিটি জিনিসের কাজ

- `figure`: পুরো একটি photo item।
- `href`: বড় ভিউয়ের জন্য ছবির ফাইল।
- `src`: gallery-তে দেখা ছবির ফাইল।
- **দুটির পথ একই রাখুন।**
- `data-photo=""`: বড় photo viewer-এ যুক্ত করে। কোনো নম্বর বা আলাদা JavaScript list লাগবে না।
- `aria-label`: link-এর বর্ণনা; সম্ভব হলে caption-এর সঙ্গে মিলিয়ে দিন।
- `alt`: বাস্তব দৃশ্যের বর্ণনা; শুধু “photo” লিখবেন না।
- `loading="lazy"`: নিচের ছবি দরকারের সময় লোড করতে সাহায্য করে।
- `figcaption`: দর্শক দেখবে এমন নাম।

Featured ছবি চাইলে `id="travel"`-এর প্রথম gallery-তে একই figure দিন; প্রথম featured ছবির পুরনো path দেখে সঠিক gallery চিনতে পারবেন। একই ছবিকে দুই জায়গায় দিলে viewer-এ সেটি দুইটি entry হিসেবেও আসতে পারে।

**English:** Upload the image and add its figure inside the intended gallery. Keep `href` and `src` identical; `data-photo` registers it automatically.

---

## ১৭. নতুন অ্যালবাম, নাম বদলানো ও মুছে ফেলা / Albums

### নতুন অ্যালবাম

1. নতুন ফোল্ডারে ছবি আপলোড করুন: `photos/travel/my-new-trip/photo-01.jpg`।
2. `index.html`-এ `<div class="archive rv">` খুঁজুন।
3. তার ভেতরে, পুরনো album-এর পরে এবং archive-এর closing `</div>`-এর আগে দিন:

```html
<details class="album">
  <summary>নিজের নতুন অ্যালবামের নাম<small>01 photo</small></summary>
  <div class="gallery">
    <figure class="g-item">
      <a href="photos/travel/my-new-trip/photo-01.jpg"
         data-photo="" aria-label="View trip photograph">
        <img src="photos/travel/my-new-trip/photo-01.jpg"
             alt="নিজের ছবির বাস্তব বর্ণনা" loading="lazy" />
        <figcaption>নিজের ছোট ক্যাপশন ↗</figcaption>
      </a>
    </figure>
  </div>
</details>
```

আরও ছবি হলে gallery-এর ভেতরে আরও figure দিন। শুরু থেকেই খোলা রাখতে `<details class="album" open>` লিখতে পারেন।

### ছবির সংখ্যা

সাইট পেজ খোলার সময় album-এর `a[data-photo]` থেকে সংখ্যা নিজে হিসাব করে। JavaScript list বা counter বদলাতে হয় না। JavaScript বন্ধ থাকলেও সঠিক fallback দেখাতে চাইলে `<small>01 photo</small>`-এর সংখ্যাটি হাতে মিলিয়ে রাখুন। ভিডিও/অডিও এই photo count-এ গণনা হয় না।

### নাম বদলানো

`summary`-র অ্যালবামের নাম বদলালেই দৃশ্যমান নাম বদলায়। শুধু display name বদলালে folder rename করার দরকার নেই। folder rename করলে ওই folder-এর প্রতিটি `href` ও `src`-ও বদলাতে হবে।

### ছবি সরানো

- gallery থেকে সংশ্লিষ্ট পুরো `<figure>...</figure>` সরান।
- শুধু `img` সরালে খালি caption/link থাকতে পারে।
- একই ফাইল অন্য কোথাও ব্যবহৃত কি না দেখে তারপর GitHub-এর আসল image file মুছুন।
- শুধু file delete করে HTML রেখে দিলে broken image হবে।

### পুরো album সরানো

সম্পূর্ণ `<details class="album">...</details>` সরান। ভুল করে পাশের album বা archive-এর closing tag মুছবেন না।

**English:** Album counts are derived from photo links. Rename the visible summary without moving files; remove complete figure or details blocks when deleting content.

---

## ১৮. প্রজেক্টে ছবি / Project photographs

বর্তমান ফোল্ডার:

- Robot Car + Automated Crane: `photos/projects/robot-car-automated-crane/`
- Water & Gas Safety Prototype: `photos/projects/water-gas-safety-prototype/`

বর্তমান project-এর ছবির container হলো `bench-photos`; Robot Car-এ দুইটি ছবির জন্য `bench-photos two`।

- বিদ্যমান project-এ নতুন ছবি: ওই project-এর ছবির container-এর ভেতরে §১৬-এর figure দিন, path প্রজেক্টের folder অনুযায়ী বদলান।
- Robot Car-এর ছবির সংখ্যা দুইটির বেশি করলে `class="bench-photos two"` থেকে শুধু `two` সরিয়ে `class="bench-photos"` করতে পারেন; তারপর ফোন ও কম্পিউটারে বিন্যাস পরীক্ষা করুন।
- নতুন সাধারণ project card-এ দুই ছবি চাইলে article-এর ভেতরে নিচের container দিন, এবং তার ভেতরে §১৬-এর মতো দুইটি figure বসান:

```html
<div class="bench-photos two">
  <!-- এখানে প্রথম ছবির সম্পূর্ণ figure বসান। -->
  <!-- এখানে দ্বিতীয় ছবির সম্পূর্ণ figure বসান। -->
</div>
```

Comment-গুলোর বদলে আসল figure দিন। `photos/projects/my-new-project/photo-01.jpg` ও `photo-02.jpg` ব্যবহার করতে পারেন—আগে সেই files আপলোড করতে হবে। ছবির caption-এ দলের কাজ/নিজের অবদান পরিষ্কার রাখুন।

**English:** Insert photo figures inside the relevant project’s photo container. Use the `two` class for two-image layouts; verify the layout after adding more images.

---

## ১৯. ভিডিও / Video

### নিজের MP4 কোথায় রাখবেন

ফাইল: `videos/my-project-demo.mp4`  
ঐচ্ছিক poster: `photos/projects/my-project/poster.jpg`

**প্রথমে files আপলোড করুন।** তারপর:

- নিজের Writing অংশে: `id="publications"` div-এর ভেতরে।
- নির্দিষ্ট project-এ: ওই project-এর article-এর ভেতরে, লেখা/stack-এর পরে।

```html
<figure class="media-item">
  <video controls playsinline preload="none"
         poster="photos/projects/my-project/poster.jpg">
    <source src="videos/my-project-demo.mp4" type="video/mp4" />
    <a href="videos/my-project-demo.mp4">Download video</a>
  </video>
  <figcaption>নিজের ভিডিওর শিরোনাম ও ছোট বিবরণ</figcaption>
  <a href="videos/my-project-demo.mp4" download>Download video ↓</a>
</figure>
```

Poster না থাকলে **পুরো `poster="..."` attribute বাদ দিন**; nonexistent ছবি রেখে দেবেন না। Video-তে `data-photo` দেবেন না। `autoplay` যোগ না করাই ভালো।

- `controls`: play, pause, volume ইত্যাদি।
- `playsinline`: ফোনে পেজের ভেতরে চলতে সাহায্য করে।
- `preload="none"`: শুরুতেই বড় ভিডিও ডাউনলোড না করতে সাহায্য করে।
- MP4 container-এর মধ্যে H.264 video + AAC audio সাধারণত বেশি compatible। শুধু extension পাল্টালে codec বদলায় না।
- ডাউনলোড link-এর ওপর click করলে browser/settings অনুযায়ী save বা open হতে পারে।

### বড় ভিডিও হলে YouTube/Vimeo link

```html
<p>
  <a class="b" href="https://www.youtube.com/watch?v=YOUR_VIDEO_ID"
     target="_blank" rel="noopener">Watch project video ↗</a>
</p>
```

নিজের পূর্ণ URL দিন। Link রাখার জন্য MP4 GitHub-এ আপলোড করতে হয় না। বর্তমান সাইটে শুধু এই link যোগ করলে embedded player তৈরি হয় না; নতুন tab-এ ভিডিও খুলবে।

### Caption / Subtitle

1. `videos/my-project-demo-bn.vtt` text file তৈরি করুন।
2. UTF-8 রাখুন এবং লিখুন:

```text
WEBVTT

00:00:00.000 --> 00:00:04.000
ভিডিওর প্রথম চার সেকেন্ডের কথাগুলো।

00:00:04.000 --> 00:00:08.000
পরের চার সেকেন্ডের কথাগুলো।
```

3. video-এর source-এর পরে, `</video>`-এর আগে দিন:

```html
<track kind="captions" src="videos/my-project-demo-bn.vtt"
       srclang="bn" label="বাংলা" default />
```

সময় ভিডিওর সঙ্গে মিলিয়ে দিন। `.vtt.txt` হয়ে গেলে চলবে না। caption না থাকলে track যোগ করবেন না।

**English:** Upload MP4 and optional poster/captions, then insert a native video player in publications or a project. Prefer externally hosted links for large videos. Do not register video as a photo.

---

## ২০. অডিও / Audio and transcript

1. MP3 আপলোড করুন: `audio/my-talk.mp3`।
2. `id="publications"`-এর ভেতরে বা সংশ্লিষ্ট project article-এ দিন:

```html
<figure class="media-item">
  <figcaption>নিজের বক্তব্য বা অডিওর শিরোনাম</figcaption>
  <audio controls preload="none">
    <source src="audio/my-talk.mp3" type="audio/mpeg" />
    <a href="audio/my-talk.mp3">Download audio</a>
  </audio>
  <a href="audio/my-talk.mp3" download>Download audio ↓</a>
  <details class="publication">
    <summary>Transcript / লিখিত বক্তব্য</summary>
    <div class="prose" lang="bn">
      <p>অডিওতে বলা কথার প্রথম অনুচ্ছেদ।</p>
      <p>পরবর্তী অনুচ্ছেদ।</p>
    </div>
  </details>
</figure>
```

MP3-এর type `audio/mpeg`; WAV হলে প্রকৃত `.wav` file ও `type="audio/wav"` দিন। ছোট MP3 বেশি সুবিধাজনক। অন্যের গান/অডিও অনুমতি ছাড়া প্রকাশ করবেন না।

Transcript অডিও শুনতে না পারা পাঠকদের সাহায্য করে এবং বিষয়টি পড়েও বোঝা যায়। এটি নিজে থেকে তৈরি হয় না—আপনাকে লিখতে হবে।

**English:** Upload audio and add a native audio player. Provide a written transcript manually. Use the MIME type matching the real file format.

---

## ২১. নিজের পেজে পুরো আর্টিকেল / On-page articles

আপনার Writing অংশের শিরোনাম **Research, writing & profiles.**। তার ভেতরে `id="publications"` নামে content রাখার জায়গা আছে। বর্তমানে এটি খালি; মন্তব্যে ভবিষ্যতের উদাহরণ আছে।

### ঠিক কোথায় বসাবেন

```html
<div class="publication-list" id="publications">
  <!-- পুরনো নির্দেশনামূলক comment থাকতে পারে। -->

  <!-- এই comment-এর বাইরে আপনার article বসান। -->
</div>
```

`</div>`-এর আগে, বাইরে থাকা `.links` profile grid-এর আগে article বসবে। আরেকটি `id="publications"` div বানাবেন না।

### বাংলা–ইংরেজি লেখার সম্পূর্ণ নমুনা

```html
<details class="publication">
  <summary>নিজের লেখার শিরোনাম / Your article title</summary>
  <time class="mono" datetime="2026-11-23">23 November 2026</time>
  <div class="prose">
    <div lang="bn">
      <h3>বাংলা</h3>
      <p>আপনার বাংলা লেখার প্রথম অনুচ্ছেদ।</p>
      <p>আপনার বাংলা লেখার দ্বিতীয় অনুচ্ছেদ।</p>
    </div>
    <div lang="en">
      <h3>English</h3>
      <p>Your first English paragraph.</p>
      <p>Your second English paragraph.</p>
    </div>
  </div>
</details>
```

শুধু বাংলা বা শুধু ইংরেজি চাইলে অন্য ভাষার পুরো inner div বাদ দিতে পারেন। শিরোনাম চাপলে খুলবে; সব সময় প্রথম থেকেই খোলা রাখতে `<details class="publication" open>` দিন।

- `datetime`: `YYYY-MM-DD`, নিজের প্রকৃত প্রকাশের তারিখ।
- time-এর মাঝের দৃশ্যমান তারিখও একই দিন রাখুন।
- নতুন paragraph: `<p>...</p>`।
- ভেতরের উপশিরোনাম: `<h3>...</h3>`। নতুন `h1` দেবেন না; পেজে প্রধান `h1` একটি থাকাই ভালো।
- bullet list: `<ul><li>প্রথম বিষয়</li><li>দ্বিতীয় বিষয়</li></ul>`।
- ছবিসহ লেখা: prose-এর ভেতরে §১৬-এর figure দিতে পারেন; আগে image upload করুন।
- আলাদা আর্টিকেল: একই publications div-এর ভেতরে আরেকটি details দিন।

এটি আলাদা blog URL তৈরি করে না; একই portfolio page-এ লেখা দেখায়। নির্দিষ্ট লেখার direct link চাইলে unique id দিন, যেমন `<details class="publication" id="my-first-article">`; তখন ঠিকানা `https://obaeedma.github.io/#my-first-article`। Hash link ওই অংশে যাবে, কিন্তু বন্ধ details নিজে থেকে খোলার নিশ্চয়তা নেই—পাঠক summary চাপতে পারেন, অথবা আপনি `open` রাখতে পারেন।

**English:** Articles live inside the existing publications container. Native details provides expandable reading. Each article stays on the same page; a unique ID enables a section link, not a separate blog page.

---

## ২২. Medium/Substack বা বাইরের লেখা / External articles

`id="publications"`-এর ভেতরে দিন:

```html
<article class="publication">
  <h3>নিজের প্রকাশিত লেখার শিরোনাম</h3>
  <p>লেখাটির বিষয় নিয়ে নিজের ছোট পরিচিতি।</p>
  <a href="https://example.com/your-actual-article"
     target="_blank" rel="noopener">Read article ↗</a>
</article>
```

**`example.com` নিজের প্রকৃত আর্টিকেল URL দিয়ে বদলান।** Profile-এর link না দিয়ে নির্দিষ্ট article-এর link দিন। Profile grid-এর Medium/Substack link আগের মতো থাকতেই পারে।

**English:** Link to the specific published article, not merely your profile. Replace sample addresses before committing.

---

## ২৩. CV ও PDF / Documents

1. আগে PDF পড়ে ব্যক্তিগত/গোপন তথ্য পরীক্ষা করুন।
2. Upload: `documents/my-cv.pdf`।
3. publications-এর ভেতরে দিন:

```html
<article class="publication">
  <h3>Curriculum Vitae / জীবনবৃত্তান্ত</h3>
  <p>নিজের CV-এর সংক্ষিপ্ত পরিচিতি বা হালনাগাদের তারিখ।</p>
  <a href="documents/my-cv.pdf" target="_blank" rel="noopener">Read CV ↗</a>
  <a href="documents/my-cv.pdf" download>Download CV ↓</a>
</article>
```

একই CV নতুন করে দিলে `my-cv.pdf` একই নামে replace করতে পারেন; link বদলাতে হবে না। অন্য নাম দিলে দুই link-এর `href` মিলিয়ে বদলান।

প্রধান অংশে CV button চাইলে `id="top"` → `.btns`-এর ভেতরে দিতে পারেন:

```html
<a class="b" href="documents/my-cv.pdf" target="_blank" rel="noopener">Read CV ↗</a>
```

নতুন button যোগ হলে মোবাইলে fit হচ্ছে কি না দেখুন। Research PDF-এর জন্য একই পদ্ধতি, প্রকৃত file name ও title ব্যবহার করুন।

**English:** Upload public PDFs to documents. Keep matching links when replacing or renaming files. Browser PDF opening/downloading depends on browser preferences.

---

## ২৪. Profile links, phone, email ও WhatsApp

### আটটি profile

বর্তমান grid-এ GitHub, Kaggle, Google Scholar, ORCID, LinkedIn, Medium, Substack, About.me আছে।

1. `EDIT: LinkedIn` বা সংশ্লিষ্ট নাম খুঁজুন।
2. ওই `a`-এর `href` আপনার সঠিক profile URL দিন।
3. নাম ও ছোট বর্ণনার text চাইলে বদলান।
4. inline SVG চিহ্নের ভেতরের code অকারণে বদলাবেন না।
5. `<head>`-এর `EDIT: পরিচয়` → JSON-এর `sameAs`-এ একই পুরনো link থাকলে সেটিও মিলিয়ে দিন।

নতুন অজানা platform-এর icon চাইলে অন্য brand-এর icon দিয়ে ভুল পরিচয় দেবেন না; icon ছাড়া সাধারণ link রাখতে পারেন। পুরনো platform-এর পুরো link copy করলে তার brand mark-ও copy হয়।

### ইমেইল

বর্তমান personal email: `swachamaobaeed@gmail.com`। বদলাতে পুরো file-এ খুঁজুন। Contact-এর দৃশ্যমান email, `mailto:...`, hero-এর Get in touch এবং JSON-LD-এর email—প্রযোজ্য সব জায়গা মিলান।

```html
<a href="mailto:YOUR-EMAIL@example.com">YOUR-EMAIL@example.com</a>
```

এখানে নমুনা email নিজের email দিয়ে বদলান। Academic email আলাদা থাকলে সেটিও আলাদাভাবে পরীক্ষা করুন।

### ফোন

বর্তমান দৃশ্যমান নম্বর: `+880 1636 317693`। link-এর নম্বর: `+8801636317693`।

- দৃশ্যমান লেখা এবং `href="tel:..."` দুটো বদলাবেন।
- JSON-LD-এর `telephone`-ও মিলিয়ে দিন।
- ফোন link মোবাইলে dialer খুলতে পারে; কম্পিউটারে উপযুক্ত app না থাকলে নাও খুলতে পারে।

**বর্তমান Phone / WhatsApp লেখা থাকা linkটি `tel:`; এটি সরাসরি WhatsApp chat খুলে দেয় না।** আলাদা WhatsApp link চাইলে contact-এর উপযুক্ত জায়গায় দিন:

```html
<a href="https://wa.me/8801636317693" target="_blank" rel="noopener">WhatsApp ↗</a>
```

এই নম্বর আপনার বর্তমান নম্বর অনুযায়ী; বদলালে আন্তর্জাতিক নম্বর দিন, `+`, স্পেস বা হাইফেন ছাড়া। WhatsApp-এ ওই নম্বর সক্রিয় থাকলে chat খুলবে।

**English:** Update visible contact text, link targets and identity metadata together. The existing `tel:` link initiates a phone call, not WhatsApp; use a separate `wa.me` link for chat.

---

## ২৫. Menu ও নতুন section

বর্তমান menu-তে সব content section নেই; menu ছোট রাখার জন্য কিছু অংশ scroll করে দেখা যায়। Education বা Journey menu-তে চাইলে existing nav-এর `<ul id="nl">`-এর ভেতরে দিন:

```html
<li><a href="#education">Education</a></li>
<li><a href="#journey">My Journey</a></li>
```

নতুন সম্পূর্ণ section সত্যিই দরকার হলে `main`-এর ভেতরে পুরনো section-এর পরে, কোনো পুরনো section-এর বাইরে দিন:

```html
<section id="my-new-section">
  <div class="w">
    <h2>নিজের নতুন অংশের নাম</h2>
    <div class="prose">
      <p>নিজের লেখা।</p>
    </div>
  </div>
</section>
```

Menu link:

```html
<li><a href="#my-new-section">New section</a></li>
```

`href`-এর `#`-এর পরের নাম ও section-এর id একই হবে। id-তে ছোট ইংরেজি ও hyphen ভালো। একই id পুনরায় ব্যবহার করবেন না। মেনু বেশি বড় হলে ফোন/ট্যাবলেট/কম্পিউটারে পরীক্ষা করুন। শুধু নতুন article-এর জন্য পুরো section বানানো দরকার নেই; publications যথেষ্ট।

**English:** Navigation links target section IDs. Keep IDs unique and add content before linking to it. Articles normally belong in publications rather than extra menu sections.

---

## ২৬. রং, dark mode ও font

বর্তমান light/dark control তৈরি আছে; নতুন paragraph, album বা publication যোগ করলে বিদ্যমান classes ব্যবহার করলে সাধারণত দুই appearance-এই মানিয়ে যাবে।

- সূর্য: বর্তমান light appearance।
- চাঁদ: dark appearance।
- প্রথমবার light; দর্শক যে পছন্দ করে সেই browser-এ মনে থাকে।
- এটি GitHub-এর account setting নয় এবং সবার জন্য একসঙ্গে dark করে না।
- browser storage বন্ধ/মুছে দিলে preference মনে নাও থাকতে পারে।

### রং কোথায়

`index.html`-এর style-এর শুরুতে `:root {` এবং `EDIT: DARK MODE` খুঁজুন।

| Variable | অর্থ / Meaning |
|---|---|
| `--paper` | প্রধান background |
| `--paper2` | দ্বিতীয় background tone |
| `--card` | card/media surface |
| `--ink` | প্রধান লেখার রং |
| `--mut` | ছোট/কম গুরুত্বের লেখার রং |
| `--line` | border/separator |
| `--teal`, `--teal2` | primary accent ও হালকা accent surface |
| `--amber`, `--amber2` | secondary accent ও surface |
| `--research-bg`, `--research-fg` | thesis অংশের background/text |
| `--serif`, `--sans`, `--mono` | heading, body ও technical font families |

যে appearance বদলাবেন তার variable-গুলোই বদলান। একই নামে দুই theme-এ ভিন্ন value থাকতে পারে। **সব জায়গায় Replace All দিয়ে একটি রং বদলানো নিরাপদ নয়।** লেখা/background-এর contrast বজায় রাখুন। নতুন content-এ `style="color:white"` বা নির্দিষ্ট সাদা background দিলে light/dark নষ্ট হতে পারে—বিদ্যমান class ব্যবহার করুন।

### Font

বর্তমান fonts: Fraunces, Instrument Sans, JetBrains Mono। Head-এ Google Fonts stylesheet link ও style-এ font variables আছে। শুধু variable বদলে নতুন font লিখলে সেটি download হয় না; font loading link-ও লাগতে পারে। Fonts unavailable হলে fallback font ব্যবহৃত হয়। অভিজ্ঞতা না থাকলে বর্তমান fonts রাখাই নিরাপদ।

Theme control-এর `name`, `value`, script-এর storage key ও viewer-এর id পরিবর্তন করবেন না। সেগুলো content নয়, কাজ করার সংযোগ।

**English:** Use existing styles so new content supports both themes. Edit the correct theme variables, preserve contrast and avoid hardcoded text/background colours in new markup.

---

## ২৭. Search information ও সহায়ক ফাইল / SEO

### `index.html`-এর head

`EDIT: SEO` খুঁজুন। প্রয়োজন হলে মিলিয়ে বদলান:

- `<title>`: browser tab ও search title-এর ভিত্তি।
- `meta name="description"`: সংক্ষিপ্ত সত্যিকারের পরিচয়।
- `og:title`, `og:description`: share preview-এর title/description।
- `canonical`, `og:url`: সাইটের মূল ঠিকানা।
- JSON-LD Person: নাম, পরিচয়, যোগাযোগ, শিক্ষা ও profile links।

নিজের মূল ঠিকানা এখন `https://obaeedma.github.io/`—ভুল করে nested upload folder-এর ঠিকানা বসাবেন না। JSON-এ quoted string, comma ও bracket খুব সাবধানে রাখুন; শেষ item-এর পরে অতিরিক্ত comma দেবেন না। না বুঝে পুরো identity script মুছবেন না।

### `robots.txt`

Search crawling-এর নির্দেশ। গোপন তথ্য রাখার ব্যবস্থা নয়; robots দিয়ে ফাইল সত্যিকার private হয় না। শুধু নতুন ছবি বা article যোগ করার জন্য এটি বদলাতে হয় না।

### `sitemap.xml`

বর্তমান portfolio এক পেজে। একই পেজের section/article বা নতুন ছবি যোগ করার জন্য নতুন sitemap URL যোগ করার দরকার নেই। ভবিষ্যতে আলাদা সত্যিকারের HTML page প্রকাশ করলে তার পূর্ণ URL যোগ করতে পারেন। `lastmod` থাকলে প্রকৃত গুরুত্বপূর্ণ পরিবর্তনের তারিখ দিন; পরিবর্তন না করে প্রতিদিন fake date বাড়াবেন না।

### Google verification

`google05d55b660994bbbd.html` না মুছে, না rename করে root-এ রাখুন। Search Console-এ settings পাল্টানোর আগে নিজের ownership verify আছে কি না দেখুন। Search result সঙ্গে সঙ্গে বদলায় না; search engine-এর পুনরায় visit দরকার।

**English:** Keep titles, descriptions and identity metadata accurate. One-page edits do not need new sitemap entries. Verification files are not content to edit; search updates are not instantaneous.

---

## ২৮. Commit ও প্রকাশের পর পরীক্ষা / Publish and verify

### প্রতিটি update-এর শেষে

1. media upload ও HTML edit—দুটো প্রযোজ্য পরিবর্তনই Commit হয়েছে কি না দেখুন।
2. root → **Actions**।
3. সর্বশেষ Pages workflow খুলুন; successfully completed হয়েছে কি না দেখুন।
4. হলুদ: কাজ অপেক্ষায়/চলমান হতে পারে। সবুজ: সফল। লাল: ব্যর্থ। সঠিক অবস্থা workflow খুলে নিশ্চিত করুন।
5. https://obaeedma.github.io/ খুলুন।
6. **Ctrl+F5** দিয়ে reload; দরকার হলে incognito window-তে খুলুন।
7. শুধু top নয়, বদলানো অংশ পর্যন্ত scroll করে দেখুন।

প্রকাশ প্রায়ই কয়েক মিনিটে হয়, কিন্তু নির্দিষ্ট ১–২ মিনিটের নিশ্চয়তা নেই। GitHub কাজ শেষ না করলে অপেক্ষা করুন; বারবার একই files upload করবেন না।

### পরীক্ষা করার তালিকা

- বাংলা অক্ষর ঠিক আছে?
- heading/paragraph ঠিক জায়গায়?
- সব ছবি দেখা যাচ্ছে এবং পুরো frame ঠিক আছে?
- gallery photo click → বড় viewer → previous/next → Escape কাজ করে?
- album summary খুলে/বন্ধ হয়? count ঠিক?
- light ও dark-এ লেখা পড়া যায়?
- ফোনে menu ও নতুন item ঠিক?
- ভিডিও ও অডিও play/pause কাজ করে?
- captions/transcript সঠিক?
- PDF ও বাইরের links খুলে?
- নতুন file-এর exact URL সরাসরি খুলে?

**English:** A commit saves files; a successful Pages deployment publishes them. Verify the actual updated content after deployment, not just the home-page header.

---

## ২৯. সমস্যা ও সমাধান / Troubleshooting

| সমস্যা | কী পরীক্ষা করবেন / What to check |
|---|---|
| আগের সাইট দেখায় | root-এর `index.html` সত্যিই বদলেছে? বাইরের package folder-এর ভেতরে পড়ে আছে? latest Actions সফল? তারপর hard refresh. |
| নতুন ছবি দেখা যায় না | file upload + commit হয়েছে? HTML figure দিয়েছেন? href/src/path/case/extension ঠিক? |
| thumbnail আসে, বড় ছবি আসে না | href ঠিক? `data-photo=""` আছে? figure-এর ভেতরে a link আছে? |
| বড় ছবি আসে, thumbnail আসে না | `img src` ভুল বা file format ভুল? |
| নতুন লেখা আসে না | comment-এর ভেতরে আছে? wrong index edited? commit/deployment হয়নি? |
| album count ভুল | figure-এর anchor-এ data-photo আছে? fallback small না মিললেও JS সক্রিয় হলে count ঠিক হওয়া উচিত; page reload করুন। |
| কোনো section অদৃশ্য/পরের অংশ এলোমেলো | অসমাপ্ত `</div>`, `</article>`, `</details>` বা comment delimiter আছে কি না দেখুন। |
| 404 | URL বা filename ভুল; file মূল folder-এ নেই; বড়/ছোট অক্ষর অমিল। |
| বাংলা এলোমেলো অক্ষর | UTF-8 save, head-এর charset utf-8 আছে কি না; ভুল encoding-এ save হয়নি কি না। |
| dark mode-এ নতুন লেখা দেখা যায় না | নতুন inline colour/background দিয়েছেন? existing prose/media classes ব্যবহার করুন। |
| ভিডিও চলে না | প্রকৃত compatible MP4/codec? path ও type ঠিক? file আসলেই upload হয়েছে? direct URL খুলুন। |
| caption আসে না | vtt format, file path, time, UTF-8 ও extension ঠিক? player-এর captions নির্বাচন করুন। |
| audio চলে না | file type ও MIME মিলেছে? direct URL খুলছে? |
| PDF download না হয়ে খুলে | browser preference; Read link কাজ করলে file accessible। |
| ফোন link কম্পিউটারে কিছু করে না | dialer/calling app নাও থাকতে পারে; ফোনে পরীক্ষা করুন। |
| GitHub Edit দেখা যায় না | নিজের account-এ signed in? নিজের repository? file options-এর `…` দেখুন। |
| upload error | per-file size, file count ও সঠিক folder পরীক্ষা; ছোট batch দিন। |
| Search preview পুরনো | search engine recrawl ও social preview cache সময় নিতে পারে; এটি Pages deployment-এর মতো নয়। |

### সরাসরি media URL দিয়ে পরীক্ষা

প্রধান ছবি: `https://obaeedma.github.io/photos/travel/portraits/portrait.jpg`  
নিজের নতুন MP4 হলে: `https://obaeedma.github.io/videos/my-project-demo.mp4`

উপরের MP4 নামটি উদাহরণ; সেই ফাইল না আপলোড করলে 404 হবে। সরাসরি ছবি খুলে গেলে file আছে; gallery না দেখালে HTML-এর path/placement দেখুন। একই নামে replace করা media browser-এ cache থাকতে পারে—private window ও hard refresh দিয়ে পরীক্ষা করুন।

**English:** Diagnose file availability separately from HTML placement. Broken paths, missing markup, comments and unfinished deployments are common causes.

---

## ৩০. ভুল হলে ফেরত নিন / Recover from mistakes

### শুধু HTML ভুল হলে: সহজ পথ

1. ব্যাকআপের পুরনো `index.html` নিন।
2. root-এ Upload files দিয়ে current `index.html` replace করুন।
3. Commit করুন, সফল deployment-এর পরে পরীক্ষা করুন।

### GitHub History থেকে লেখা ফেরত

1. `index.html` খুলুন → **History**।
2. ভুলের আগের সঠিক revision খুলুন।
3. সেই revision-এর file view/raw contents খুলুন; diff-এর `+`/`-` চিহ্নসহ copy করবেন না।
4. পুরনো সঠিক সম্পূর্ণ HTML copy করুন।
5. current main-এর `index.html` Edit খুলে ভুল লেখার বদলে সঠিক code বসান।
6. নতুন Commit দিন, যেমন `Restore working portfolio HTML`।

এই পদ্ধতি নতুন revision তৈরি করে; পুরনো history মুছে দেয় না। GitHub-এ এক ক্লিকে “restore” সব সময় থাকে ধরে নেবেন না। ছবি মুছে ফেললে পুরনো backup থেকে matching ছবিও ফিরিয়ে দিন।

**English:** Restore known-good content through a new commit. A matching media backup is necessary if photos were deleted or renamed.

---

## ৩১. নিরাপত্তা, সীমা ও ছোট চেকলিস্ট / Safe routine

### কী কখনো রাখবেন না

- password, API secret, private key, banking details।
- NID/passport scan, ব্যক্তিগত address বা অন্যের personal information অনুমতি ছাড়া।
- public হওয়া উচিত নয় এমন thesis data বা confidential documents।

GitHub Pages-এর files public URL দিয়ে খোলা যায়; menu-তে link না থাকলেও private নয়। Public Git history-তেও মুছে দেওয়া file-এর পুরনো copy থাকতে পারে। তাই গোপন তথ্য ভুল করে upload হলে শুধু menu link/delete যথেষ্ট ধরে নেবেন না; প্রকাশিত credential হলে সেটি বদলাতে হবে।

### বড় file ও performance

- GitHub browser upload সাধারণত প্রতি file **25 MiB পর্যন্ত**; তার নিচে রাখাই সুবিধাজনক। সীমা বদলালে GitHub-এর বর্তমান upload নির্দেশ মানবেন।
- অনেক file একসঙ্গে upload না হলে ছোট batch ব্যবহার করুন।
- খুব বড় video GitHub-এ না রেখে YouTube/Vimeo link ব্যবহার করুন।
- ছবি camera-এর আসল বিশাল file না দিয়ে web-friendly copy দিন। সাধারণত long edge 1600–2000 px ও উপযুক্ত JPEG quality ভালো শুরু; দৃশ্যের detail অনুযায়ী সিদ্ধান্ত নিন।
- screenshot/diagram-এ PNG বা WebP উপযুক্ত হতে পারে; প্রকৃত extension ও HTML path মিলিয়ে রাখুন।
- JPEG করলে transparency থাকে না।
- animated/heavy content অকারণে যোগ করলে page ধীর হয়।
- GitHub Pages প্রকৃত database, visitor upload বা private admin system নয়; এই নির্দেশিকা সেগুলো যোগ করে না।

### এক নজরে কাজের recipe

| কাজ | করণীয় |
|---|---|
| পুরনো ছবি replace | একই folder + একই filename upload → commit → alt/caption প্রয়োজনে edit |
| নতুন ছবি | file upload → gallery-তে figure + data-photo → commit |
| নতুন album | folder/files → archive-তে details.album → commit |
| নতুন project | projects-এ article → প্রকৃত তথ্য/link/media → commit |
| বাংলা/English লেখা | publications-এ details.publication + prose → commit |
| audio | audio file → audio controls + transcript → commit |
| video | MP4/poster/caption → video controls → commit |
| CV/PDF | documents file → publication/link → commit |
| profile link | href + প্রযোজ্য sameAs → commit |
| phone/email | দৃশ্যমান লেখা + link + JSON → commit |

### শেষ দশটি প্রশ্ন

- [ ] ব্যাকআপ আছে?
- [ ] সঠিক root ও main-এ কাজ করেছি?
- [ ] নতুন media file upload করেছি?
- [ ] path ও বড়/ছোট অক্ষর মিলে?
- [ ] sample text ও sample URL নিজের তথ্য দিয়ে বদলেছি?
- [ ] HTML comment-এর বাইরে content বসিয়েছি?
- [ ] tag ও parent container ঠিক রেখেছি?
- [ ] সব পরিবর্তন Commit করেছি এবং deployment সফল?
- [ ] ফোন–কম্পিউটার ও light–dark-এ পরীক্ষা করেছি?
- [ ] কোনো গোপন/অন্যের অনুমতিহীন তথ্য প্রকাশ করছি না?

**English:** Back up, upload media, edit markup, commit, wait for success and test both themes on phone and desktop. Keep public content safe and media reasonably small.

---

## ৩২. বর্তমান ছবির পূর্ণ তালিকা / Current photo inventory

নিচের তালিকা চূড়ান্ত upload package থেকে নেওয়া। এতে **৬২টি ছবি** আছে। পরে নিজের নতুন ছবি যোগ করলে এই guide/CSV নিজে থেকে বদলাবে না; চাইলে inventory হালনাগাদ করুন। Album-এর live count আলাদা করে নিজে হিসাব হয়।

কোন ছবি বদলাবেন বুঝতে প্রথমে এই path GitHub-এ খুলে file preview দেখুন। **পুরনো filename দেখে আন্দাজ নয়—আসল ছবি মিলিয়ে নিন।**


### `photos/profile/` — 2 ছবি / photographs

| সঠিক পথ / Exact path | Caption / পরিচয় |
|---|---|
| `photos/travel/portraits/portrait.jpg` | M A Obaeed · Dhaka |
| `photos/travel/portraits/beyond-the-desk.jpg` | Beyond the desk · always curious. |

### `photos/projects/robot-car-automated-crane/` — 2 ছবি / photographs

| সঠিক পথ / Exact path | Caption / পরিচয় |
|---|---|
| `photos/projects/robot-car-automated-crane/the-crane-build.jpg` | The crane build ↗ |
| `photos/projects/robot-car-automated-crane/team-tablet-control.jpg` | Team & tablet control ↗ |

### `photos/projects/water-gas-safety-prototype/` — 3 ছবি / photographs

| সঠিক পথ / Exact path | Caption / পরিচয় |
|---|---|
| `photos/projects/water-gas-safety-prototype/the-bench-prototype.jpg` | The bench prototype ↗ |
| `photos/projects/water-gas-safety-prototype/debugging-the-firmware.jpg` | Debugging the firmware ↗ |
| `photos/projects/water-gas-safety-prototype/building-with-the-team.jpg` | Building with the team ↗ |

### `photos/leadership/` — 1 ছবি / photographs

| সঠিক পথ / Exact path | Caption / পরিচয় |
|---|---|
| `photos/leadership/club-members-organisers-campus.jpg` | Club members & organisers · campus |

### `photos/travel/featured/` — 8 ছবি / photographs

| সঠিক পথ / Exact path | Caption / পরিচয় |
|---|---|
| `photos/travel/featured/long-exposure-falls.jpg` | Long-exposure falls ↗ |
| `photos/travel/featured/the-canyon.jpg` | The canyon ↗ |
| `photos/travel/featured/ridges-at-dawn.jpg` | Ridges at dawn ↗ |
| `photos/travel/featured/night-in-the-hills.jpg` | Night in the hills ↗ |
| `photos/travel/featured/ratargul.jpg` | Ratargul ↗ |
| `photos/travel/featured/coral-shore.jpg` | Coral shore ↗ |
| `photos/travel/featured/green-archway.jpg` | Green archway ↗ |
| `photos/travel/featured/hill-village.jpg` | Hill village ↗ |

### `photos/travel/hills-light/` — 18 ছবি / photographs

| সঠিক পথ / Exact path | Caption / পরিচয় |
|---|---|
| `photos/travel/hills-light/alutila.jpg` | Alutila ↗ |
| `photos/travel/hills-light/hill-cabin.jpg` | Hill cabin ↗ |
| `photos/travel/hills-light/morning-mist.jpg` | Morning mist ↗ |
| `photos/travel/hills-light/first-light.jpg` | First light ↗ |
| `photos/travel/hills-light/green-hills.jpg` | Green hills ↗ |
| `photos/travel/hills-light/flowers.jpg` | Flowers ↗ |
| `photos/travel/hills-light/hill-viewpoint.jpg` | Hill viewpoint ↗ |
| `photos/travel/hills-light/hill-afternoon.jpg` | Hill afternoon ↗ |
| `photos/travel/hills-light/under-the-trees.jpg` | Under the trees ↗ |
| `photos/travel/hills-light/hill-morning.jpg` | Hill morning ↗ |
| `photos/travel/hills-light/misty-hills.jpg` | Misty hills ↗ |
| `photos/travel/hills-light/hill-village.jpg` | Hill village ↗ |
| `photos/travel/hills-light/across-the-valley.jpg` | Across the valley ↗ |
| `photos/travel/hills-light/green-valley.jpg` | Green valley ↗ |
| `photos/travel/hills-light/golden-hour.jpg` | Golden hour ↗ |
| `photos/travel/hills-light/bandarban.jpg` | Bandarban ↗ |
| `photos/travel/hills-light/chandranath.jpg` | Chandranath ↗ |
| `photos/travel/hills-light/chimbuk.jpg` | Chimbuk ↗ |

### `photos/travel/sea-lakes/` — 5 ছবি / photographs

| সঠিক পথ / Exact path | Caption / পরিচয় |
|---|---|
| `photos/travel/sea-lakes/coral-coast.jpg` | Coral coast ↗ |
| `photos/travel/sea-lakes/chira-deep.jpg` | Chira Deep ↗ |
| `photos/travel/sea-lakes/madhoppur-lake.jpg` | Madhoppur Lake ↗ |
| `photos/travel/sea-lakes/mohesh-khali.jpg` | Mohesh Khali ↗ |
| `photos/travel/sea-lakes/niladri-lake.jpg` | Niladri Lake ↗ |

### `photos/travel/trails-friends/` — 12 ছবি / photographs

| সঠিক পথ / Exact path | Caption / পরিচয় |
|---|---|
| `photos/travel/trails-friends/krishnochura.jpg` | Krishnochura ↗ |
| `photos/travel/trails-friends/waterfall-trail.jpg` | Waterfall trail ↗ |
| `photos/travel/trails-friends/woodland-walk.jpg` | Woodland walk ↗ |
| `photos/travel/trails-friends/garden-pause.jpg` | Garden pause ↗ |
| `photos/travel/trails-friends/forest-trail.jpg` | Forest trail ↗ |
| `photos/travel/trails-friends/tree-lined-road.jpg` | Tree-lined road ↗ |
| `photos/travel/trails-friends/green-tunnel.jpg` | Green tunnel ↗ |
| `photos/travel/trails-friends/under-the-canopy.jpg` | Under the canopy ↗ |
| `photos/travel/trails-friends/on-the-trail.jpg` | On the trail ↗ |
| `photos/travel/trails-friends/mati-ta.jpg` | Mati Ta ↗ |
| `photos/travel/trails-friends/waterfall-friends.jpg` | Waterfall & friends ↗ |
| `photos/travel/trails-friends/trekking-friends.jpg` | Trekking friends ↗ |

### `photos/travel/portraits/` — 9 ছবি / photographs

| সঠিক পথ / Exact path | Caption / পরিচয় |
|---|---|
| `photos/travel/portraits/portrait.jpg` | Portrait ↗ |
| `photos/travel/portraits/a-quiet-pause.jpg` | A quiet pause ↗ |
| `photos/travel/portraits/m-a-obaeed.jpg` | M A Obaeed ↗ |
| `photos/travel/portraits/beyond-the-desk.jpg` | Beyond the desk ↗ |
| `photos/travel/portraits/caf-moment.jpg` | Café moment ↗ |
| `photos/travel/portraits/jolsiri.jpg` | Jolsiri ↗ |
| `photos/travel/portraits/a-day-outdoors.jpg` | A day outdoors ↗ |
| `photos/travel/portraits/garden-portrait.jpg` | Garden portrait ↗ |
| `photos/travel/portraits/in-the-garden.jpg` | In the garden ↗ |

### `photos/travel/campus/` — 2 ছবি / photographs

| সঠিক পথ / Exact path | Caption / পরিচয় |
|---|---|
| `photos/travel/campus/campus-friends.jpg` | Campus friends ↗ |
| `photos/travel/campus/campus-memories.jpg` | Campus memories ↗ |

---

**শেষ কথা / Final principle:** ফাইল কোথায় আছে → HTML-এ সঠিক পথ ও অংশ → Commit → সফল প্রকাশ → পরীক্ষা। এই পাঁচটি ধাপ মনে রাখলে বেশিরভাগ দৈনন্দিন কাজ নিজে করতে পারবেন।
