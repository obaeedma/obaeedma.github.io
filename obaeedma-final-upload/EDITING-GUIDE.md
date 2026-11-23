# M A Obaeed — নিজের পোর্টফোলিও সম্পাদনার গাইড

## নতুন প্যাকেজ: v12

এই সংস্করণে ছবিগুলো বিষয়ভিত্তিক ফোল্ডারে গুছানো। পুরনো `index.html`-এর সঙ্গে শুধু নতুন ছবি বা নতুন `index.html`-এর সঙ্গে শুধু পুরনো ছবি ব্যবহার করবেন না—নতুন প্যাকেজের দুটোই একসঙ্গে আপলোড করুন। আগের সংস্করণের ফাইল নিজের কাছে ব্যাকআপ রাখুন।

## প্রথমবার আপলোড

1. ZIP খুলুন; ভেতরের `index.html`, `photos/`, `videos/`, `audio/`, `documents/`, `.nojekyll`, `robots.txt`, `sitemap.xml` ও Google verification ফাইল রিপোজিটরির মূল জায়গায় রাখুন। ZIP ফাইলটি নিজে আপলোড করলে সাইট বদলাবে না।
2. `index_v12.html` আলাদাভাবে ডাউনলোড করলে সেটির নাম `index.html` করুন। ছবির জন্য সম্পূর্ণ ZIP-এর `photos/` ফোল্ডারও দরকার।
3. GitHub-এ **Add file → Upload files → Commit changes**। পরে **Actions**-এ Pages deployment শেষ হওয়া দেখুন।
4. নিজের সাইট খুলে Ctrl+F5 দিন। কোনো ইনস্টল বা build লাগবে না।

## কোডের তিনটি অংশ

- `<head>`: সার্চের নাম, বর্ণনা, ফন্ট ও পরিচয়ের তথ্য।
- `<style>`: রং, ছবির মাপ, ফন্ট ও বিন্যাস।
- `<body>`: আপনার লেখা, প্রজেক্ট, শিক্ষা, ছবি ও যোগাযোগ। শেষে `<script>` আছে: মেনু, ছবি বড় করে দেখা ও অ্যানিমেশন।

GitHub-এ `index.html` খুলুন → পেন্সিল/Edit → Ctrl+F দিয়ে `EDIT:` বা অংশের নাম খুঁজুন → বদলান → Commit changes। আগে ফাইলের কপি রাখুন। মন্তব্যগুলো ওয়েবসাইটে দেখা যায় না।

## কোন তথ্য কোথায়

| যা বদলাবেন | যে লেখা খুঁজবেন |
|---|---|
| ওপরের নাম ও মেনু | `EDIT: মেনু` |
| প্রধান নাম, পেশা ও অবস্থান | `id="top"` |
| প্রধান ছবি | `EDIT: প্রধান ছবি` |
| নিজের পরিচয় ও দ্বিতীয় ছবি | `id="profile"` |
| জীবনের গল্প | `id="journey"` |
| থিসিস | `id="thesis"` |
| প্রজেক্ট | `id="projects"` |
| দক্ষতা | `id="skills"` |
| শিক্ষা | `id="education"` |
| নেতৃত্ব | `id="leadership"` |
| পুরস্কার | `id="achievements"` |
| ভ্রমণ, ছবি ও অ্যালবাম | `id="travel"` |
| প্রোফাইল/লেখার লিংক | `id="writing"` |
| ফোন ও ইমেইল | `id="contact"` |
| পুরো পেজের রং | `:root` |

## লেখা বদলানো

## বর্তমান রং ও ডার্ক মোড

ওপরের সূর্য চিহ্নে আগের রং, চাঁদ চিহ্নে ডার্ক মোড। দর্শকের নির্বাচন একই ব্রাউজারে মনে থাকে; প্রথমবার আগের রং দেখায়। রং বদলাতে `EDIT: DARK MODE` খুঁজুন; বর্তমান রং `:root`-এ আছে। নতুন লেখা বা অ্যালবাম যোগ করলেও দুই রঙে দেখা যাবে।

প্রোফাইল লিংকগুলোর পরিচিত চিহ্ন কোডের ভেতরেই আছে, তাই আলাদা ছবি আপলোডের দরকার নেই। লিংক বদলাতে `EDIT: GitHub`, `EDIT: Kaggle` বা সংশ্লিষ্ট নাম খুঁজুন।

## লেখা বদলানোর নিয়ম

`<h3>পুরনো শিরোনাম</h3>`-তে শুধু মাঝের লেখা বদলান। নতুন অনুচ্ছেদ দিতে `<p>নতুন লেখা</p>` যোগ করুন। লেখায় `&` থাকলে `&amp;`, `<` থাকলে `&lt;`, `>` থাকলে `&gt;` লিখুন। ট্যাগের শুরু/শেষ মুছবেন না।

## ছবি বদলানো

সবচেয়ে সহজ: নতুন ছবি একই ফাইলের নামে `photos/`-এ আপলোড করুন। যেমন `photos/profile/pick-hero.jpg` বদলালে প্রধান ছবি বদলাবে; `photos/profile/pick-profile.jpg` বদলালে About Me ছবি বদলাবে। সত্যিই JPEG হলে `.jpg` দিন; PNG ফাইলকে শুধু নাম বদলে JPEG করবেন না।

অন্য নাম ব্যবহার করলে সংশ্লিষ্ট `img src` বদলান; ক্লিকযোগ্য ছবিতে `a href`-ও একই নাম দিন। `alt`-এ ছবির সঠিক বর্ণনা এবং `figcaption`-এ ছোট নাম দিন। নামের বড়/ছোট অক্ষর মিলতে হবে। ফাইলের নাম ছোট ইংরেজিতে, স্পেস ছাড়া রাখুন।

## নতুন ছবি যোগ করা

1. `photos/travel/my-album/new-photo.jpg` আপলোড করুন।
2. পছন্দের অ্যালবামের `<div class="gallery">`-এর ভেতরে নিচের সম্পূর্ণ অংশ বসান:

```html
<figure class="g-item">
  <a href="photos/travel/my-album/new-photo.jpg" data-photo="" aria-label="View New photograph">
    <img src="photos/travel/my-album/new-photo.jpg" alt="ছবির সঠিক বর্ণনা" loading="lazy" />
    <figcaption>New photograph ↗</figcaption>
  </a>
</figure>
```

3. অ্যালবামের ছবির সংখ্যা পেজ খোলার সময় নিজে থেকে আপডেট হবে; আলাদা তালিকা বদলাতে হবে না। JavaScript বন্ধ থাকা দর্শকদের জন্য চাইলে `<small>`-এ সংখ্যাটিও মিলিয়ে রাখতে পারেন।

`data-photo=""` থাকলে ছবিটি বড় করে খুলবে এবং আগের/পরের ছবির তালিকায় নিজে যোগ হবে; কোনো নম্বর বা JavaScript তালিকা বদলাতে হবে না। ছবি বদলানোর পর নতুন করে পেজ খুলে পরীক্ষা করুন।

## নতুন অ্যালবাম

`<div class="archive rv">`-এর ভেতরে বসান:

```html
<details class="album">
  <summary>New album<small>01 photo</small></summary>
  <div class="gallery">
    <!-- এখানে ওপরের সম্পূর্ণ figure অংশ বসান -->
  </div>
</details>
```

## ভিডিও যোগ করা

`videos/` ফোল্ডার তৈরি করে `project-demo.mp4` আপলোড করুন। একটি কভার ছবি `photos/project-poster.jpg` নামে রাখুন। প্রজেক্টের ভেতরে বা কোনো gallery-তে বসান:

```html
<figure class="g-item">
  <video controls playsinline preload="metadata" poster="photos/project-poster.jpg">
    <source src="videos/project-demo.mp4" type="video/mp4" />
    <a href="videos/project-demo.mp4">Download video</a>
  </video>
  <figcaption>Project demonstration</figcaption>
</figure>
```

MP4-এ H.264 ভিডিও/AAC অডিও রাখলে অধিকাংশ ব্রাউজারে চলে। ভিডিওতে `data-photo` দেবেন না। GitHub-এর ব্রাউজার আপলোডে প্রতি ফাইল 25 MiB-এর নিচে রাখুন; বড় ভিডিও হলে YouTube/Vimeo-তে রেখে নিচের মতো লিংক দিন:

```html
<a class="b" href="YOUR_VIDEO_URL" target="_blank" rel="noopener">Watch video ↗</a>
```

## নতুন প্রজেক্ট

`<div class="projects">`-এর ভেতরে একটি সম্পূর্ণ `<article class="proj rv">…</article>` কপি করুন। শিরোনাম, বর্ণনা, দক্ষতা ও লিংক বদলান। ছবি/ভিডিওর ওপরের অংশও সেই article-এর ভেতরে রাখতে পারেন। কোনো অজানা অর্জন বা প্রযুক্তি যোগ করবেন না।

নতুন দক্ষতা: `<span class="chip">New skill</span>`। নতুন শিক্ষা: `ol.tl`-এ একটি `li` কপি। নতুন নেতৃত্ব: একটি `div.row` কপি। নতুন পুরস্কার: একটি `div.aw` কপি।

## ফোন, ইমেইল ও নতুন মেনু

- ফোনের দৃশ্যমান লেখা এবং `href="tel:+880…"` দুটোই বদলান। ইমেইলের লেখা ও `mailto:`-ও একসঙ্গে বদলান।
- নাম/যোগাযোগ বদলালে head-এর পরিচয়ের JSON-ও মিলিয়ে বদলান।
- নতুন অংশে একটি আলাদা `id` দিন। মেনুর `href="#new-section"` ও অংশের `id="new-section"` মিলতে হবে; পুরনো id বদলালে সংশ্লিষ্ট মেনুও বদলান।

## শেষে যা পরীক্ষা করবেন

- মোবাইল ও কম্পিউটারে নাম, লেখা ও ছবি ঠিক আছে কি না।
- প্রতিটি নতুন ছবি ক্লিক করে বড় ভিউ খুলুন; তীর ও Escape পরীক্ষা করুন।
- ভিডিও চালান; ছবির ফাইল ও ভিডিও সত্যিই আপলোড হয়েছে কি না দেখুন।
- ফোন, ইমেইল, প্রজেক্ট ও মেনুর লিংক খুলুন।
- ভুল হলে GitHub-এর পুরনো commit থেকে আগের ফাইলের লেখা ফিরিয়ে নিন। কোনো secret/password কোডে রাখবেন না।

এটি GitHub থেকে সম্পাদনাযোগ্য স্থির সাইট; দর্শকদের জন্য ছবি/ভিডিও আপলোডের ফর্ম বা পরিচালনার প্যানেল নয়।

## ফোল্ডারগুলো কীভাবে গুছানো

```text
index.html                         পুরো পোর্টফোলিও: লেখা + ডিজাইন + কাজ করার নিয়ম
photos/
  profile/                         প্রধান ছবি ও About Me
  leadership/                      নেতৃত্বের গ্রুপ ছবি
  projects/
    robot-car-automated-crane/      রোবট প্রজেক্টের ছবি
    water-gas-safety-prototype/     সেন্সর প্রজেক্টের ছবি
  travel/
    featured/                      প্রথমে দেখা ভ্রমণের ছবি
    hills-light/                   পাহাড়ের অ্যালবাম
    sea-lakes/                     সমুদ্র ও হ্রদ
    trails-friends/                ট্রেইল ও বন্ধু
    portraits/                    অন্য পোর্ট্রেট
    campus/                       ক্যাম্পাস
videos/                            নিজের ভিডিও + caption ফাইল
audio/                            নিজের অডিও
documents/                        CV, PDF, গবেষণা নথি
PHOTO-INDEX.csv                     আগের ছবির নাম → নতুন পথ → ক্যাপশন
```

উপরের `audio/` ও `documents/`-ও মূল ফোল্ডারেই থাকবে। প্রতিটি ছবির আসল নতুন পথ `PHOTO-INDEX.csv`-তে আছে। ছবির নাম ছোট ইংরেজিতে, স্পেস ছাড়া রাখা হয়েছে। নিজের নতুন অ্যালবাম বা প্রজেক্টের জন্য একইভাবে নতুন সাবফোল্ডার বানান। `../` ব্যবহার না করে মূল `index.html` থেকে পুরো পথ লিখুন।

## সবচেয়ে সহজ দৈনন্দিন পরিবর্তন

**পুরনো ছবি বদল:** যে ছবি বদলাবেন তার বর্তমান পথ খুঁজুন; নতুন ছবিকে একই নাম ও একই ফোল্ডারে আপলোড করুন। কোড বদলানোর দরকার নেই। ছবির বিষয় বদলালে `alt` ও `figcaption`-ও বদলান।

**নতুন ছবি:** ফাইলটি আগে আপলোড করুন, তারপর `PHOTO TEMPLATE` কপি করুন। `href` ও `src`-এ একই নতুন পথ দিন। `data-photo=""` রাখুন।

**নতুন লেখা:** Ctrl+F → `FUTURE CONTENT` → পছন্দের উদাহরণ কপি করে `id="publications"`-এর ভেতরে বসান। উদাহরণের চারপাশের `<!--` এবং `-->` কপি করবেন না—সেগুলো থাকলে লেখা লুকিয়ে থাকবে।

## নিজের পেজে আর্টিকেল বা ছোট লেখা

নিচের অংশ `publication-list`-এর ভেতরে বসান। প্রজেক্টের বিবরণে শুধু নতুন `p` যোগ করলেও হবে।

```html
<details class="publication">
  <summary>আপনার লেখার শিরোনাম</summary>
  <time class="mono" datetime="2026-11-23">23 November 2026</time>
  <div class="prose" lang="bn">
    <p>নিজের প্রথম অনুচ্ছেদ।</p>
    <p>দ্বিতীয় অনুচ্ছেদ।</p>
  </div>
</details>
```

শিরোনামে ক্লিক করলে সম্পূর্ণ লেখা খুলবে। শুরু থেকেই খোলা রাখতে `<details class="publication" open>` লিখুন। প্রকাশের তারিখ নিজেরটি দিন। ছবি চাইলে ভেতরে সম্পূর্ণ `figure.g-item` যোগ করতে পারেন। বাংলা লেখায় `lang="bn"`, ইংরেজিতে `lang="en"` দিন।

Medium/Substack-এ লেখা থাকলে `EXTERNAL ARTICLE TEMPLATE` ব্যবহার করুন। নিজের প্রোফাইলের বদলে ওই লেখাটির নির্দিষ্ট ঠিকানা দিন। কোনো লেখা না দিলে এই অংশ পেজে অপ্রয়োজনীয় খালি শিরোনাম দেখাবে না।

## অডিও যোগ করা

নিজের MP3 ফাইল `audio/my-talk.mp3` নামে আপলোড করে নিচের অংশ publications বা প্রজেক্টের ভেতরে বসান।

```html
<figure class="media-item">
  <figcaption>আমার বক্তব্য</figcaption>
  <audio controls preload="none">
    <source src="audio/my-talk.mp3" type="audio/mpeg" />
  </audio>
  <a href="audio/my-talk.mp3" download>Download audio ↓</a>
  <details class="publication">
    <summary>Transcript</summary>
    <div class="prose"><p>বক্তব্যের সম্পূর্ণ লেখা।</p></div>
  </details>
</figure>
```

এতে প্লে, পজ, সময় ও শব্দের নিয়ন্ত্রণ ব্রাউজার নিজেই দেয়। অডিও নিজে থেকে বাজবে না। অডিও শুনতে না পারা পাঠকদের জন্য লিখিত বক্তব্য রাখুন। WAV হলে ফাইল `.wav` ও `type="audio/wav"` হবে; ছোট MP3 বেশি সুবিধাজনক।

## ভিডিওর আরও ভালো উদাহরণ

`media-item` ব্যবহার করলে নিচে ক্যাপশন ও ডাউনলোড লিংক পরিষ্কার থাকে।

```html
<figure class="media-item">
  <video controls playsinline preload="none" poster="photos/projects/my-project/poster.jpg">
    <source src="videos/project-demo.mp4" type="video/mp4" />
    <track kind="captions" src="videos/project-demo-bn.vtt" srclang="bn" label="বাংলা" />
  </video>
  <figcaption>আমার প্রজেক্টের প্রদর্শন</figcaption>
  <a href="videos/project-demo.mp4" download>Download video ↓</a>
</figure>
```

Caption না থাকলে `track` লাইন বাদ দিন। Caption রাখতে `videos/project-demo-bn.vtt` নামে ফাইল বানিয়ে এমনভাবে লিখুন:

```text
WEBVTT

00:00:00.000 --> 00:00:04.000
নিজের ভিডিওর এই সময়ের কথাগুলো।
```

প্রতিটি সময়ের অংশের মধ্যে একটি ফাঁকা লাইন রাখুন। দীর্ঘ/বড় ভিডিও YouTube/Vimeo-তে দিয়ে সরাসরি লিংক রাখুন; বড় ভিডিও GitHub-এর আপলোড সীমা ও সাইটের গতি দুটোতেই সমস্যা করতে পারে।

## PDF বা CV যোগ করা

```html
<article class="publication">
  <h3>আমার CV</h3>
  <a href="documents/my-cv.pdf" target="_blank" rel="noopener">Read CV ↗</a>
</article>
```

আগে `documents/my-cv.pdf` আপলোড করুন। নিজের ফোন/ঠিকানা আছে কি না দেখে তারপর প্রকাশ করুন। GitHub Pages-এর সব ফাইল প্রকাশ্য—গোপন নথি, পাসওয়ার্ড বা ব্যক্তিগত চাবি রাখবেন না।

## GitHub থেকে নতুন ফাইল আপলোড

1. রিপোজিটরির সঠিক ফোল্ডারে যান।
2. **Add file → Upload files** → নিজের ফাইল দিন → **Commit changes**।
3. এরপর `index.html` খুলে পেন্সিল/Edit চাপুন; সংশ্লিষ্ট উদাহরণ বসিয়ে পথ মিলিয়ে Commit করুন।
4. **Actions**-এ deployment শেষ হলে সাইট খুলুন; Ctrl+F5 দিন।
5. নতুন ছবি বড় করে দেখুন; ভিডিও ও অডিও প্লে করুন; নতুন আর্টিকেল খুলুন।

ফোল্ডার না থাকলে পিসিতে সেই কাঠামো বানিয়ে ফোল্ডারসহ আপলোড করুন। ZIP ফাইল নিজে আপলোড করলে পেজ বা ছবি বদলাবে না; Extract করে ভেতরের ফাইল দিতে হবে।

**এটি দর্শকদের আপলোড করার ফর্ম নয়।** আপনার নিজের ছবি/মিডিয়া/লেখা GitHub দিয়ে প্রকাশের ব্যবস্থা। তাই কোনো নতুন লগইন, মাসিক পরিচালনা ব্যবস্থা বা ইনস্টল দরকার নেই।
