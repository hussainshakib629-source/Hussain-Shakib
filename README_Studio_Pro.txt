Sakib Studio Pro v1.0.5: ফ্রি অনলাইন লিংকে তোলার ধাপ (GitHub Pages)
=================================================================
এই ফোল্ডারের সবগুলো ফাইল একসাথে আপলোড করতে হবে:
index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, icon-maskable-512.png

ধাপ ১: github.com-এ লগইন করুন (Chrome-এ। কঠিন লাগলে মেনু থেকে "Desktop site" চালু করুন)।
ধাপ ২: নতুন Repository বানান (নাম সাধারণ কিছু, Public)। আগের রিপো থাকলে সেটাই ব্যবহার করুন।
ধাপ ৩: "Add file > Upload files" দিয়ে ZIP আনজিপ করে ৬টা ফাইলই আপলোড দিন। আগের ফাইল থাকলে Replace হবে। Commit changes চাপুন।
ধাপ ৪: Settings > Pages। Source: "Deploy from a branch"। Branch: main, ফোল্ডার: /(root)। Save চাপুন।
ধাপ ৫: ১-২ মিনিট পর লিংক চালু হবে। লিংক খুললেই সরাসরি হোম স্ক্রিন আসবে।
ধাপ ৬: Chrome মেনু > "Install app" বা "Add to Home screen"।

আপডেট না দেখালে: পেজ একবার রিফ্রেশ করুন, দরকার হলে Chrome-এর "Site settings" থেকে ডেটা ক্লিয়ার করুন।

কীভাবে চলে:
- হোম স্ক্রিনে সব টুল ক্যাটাগরি অনুযায়ী বড় কার্ডে থাকে। কার্ডে চাপলে টুল ডান পাশে খোলে, বাম পাশে মেনু আসে।
- হোমে ফিরতে: বাম ওপরের ছবি/লোগো, ওপরের 🏠 বোতাম, নিচের Home বোতাম, অথবা ডান নিচের ভাসমান 🏠 বোতাম।
- অফলাইনে চালাতে: index.html ফাইলটা সরাসরি Chrome-এ খুলুন। সব টুল ওই ফাইলের ভেতরেই আছে।
- Metadata Generator ও Stock Radar-এ API key লাগে আর ইন্টারনেট দরকার। বাকি টুল অফলাইনে চলে।

সতর্কতা:
- Repository Public হলে ফাইল কেউ খুঁজে পেলে দেখতে পারে। ফাইলের ভেতরে API key লিখবেন না। টুলে বসানো key শুধু আপনার ব্রাউজারে সেভ থাকে।

পাসওয়ার্ড লক (v8):
- লক করা টুল: Lumen Loop, Motion Atelier, Motion Metrics, Christmas Loop (ভিডিও টুল ৪টা), Background Studio Pro, Lumi Bloom, Frostlight, Seamless Pattern Studio, Merry Tiles Christmas। বাকিগুলো খোলা।
- লক করা টুলে চাপলে পাসওয়ার্ড চাইবে। একবার আনলক করলে ৯টাই একসাথে খুলে যায়।
- "এই ডিভাইসে মনে রাখো" টিক দিলে ওই ফোন বা পিসিতে আর চাইবে না।
- লক করা টুলগুলো ফাইলের ভেতরে এনক্রিপ্ট করা আছে, তাই সোর্স দেখে সরাসরি পড়া যাবে না। তবে ৫ সংখ্যার পাসওয়ার্ড সাধারণ সুরক্ষা, খুব দৃঢ় নয়।
- পাসওয়ার্ড বদলাতে হলে আমাকে নতুন পাসওয়ার্ড বলুন, নতুন জিপ বানিয়ে দেব।

v1.0.1 পরিবর্তন:
- Glitterfall Studio: SVG এখন আসল gradient আর opacity দিয়ে বানানো হয়, তাই প্রিভিউর মতো দেখায়। গ্লো-র প্রতিটা কণা একটাই অবজেক্ট, লেয়ার ভাঙে না। Glow-র ভেতরে Flake_Halos, Sparkles, Bokeh সাব-গ্রুপ।
- সব টুলের SVG এক্সপোর্টে (জিপ/প্যাক সহ) এখন একটা সাধারণ ক্লিন-আপ চলে: খালি গ্রুপ বাদ, অকারণ গভীর গ্রুপ খুলে দেওয়া, নামহীন লেয়ারে নাম বসানো।
- EPS-এ transparency রাখা যায় না। সবচেয়ে ভালো EPS চাইলে SVG নামিয়ে Illustrator-এ খুলে Save As EPS করুন।
- Christmas Loop (পাসওয়ার্ড-লক করা টুল) অপরিবর্তিত আছে।

v1.0.2 পরিবর্তন:
- সরানো হয়েছে: Adobe Stock Radar, Sakib Magnify, Sakib Upscale Studio।
- নতুন: Sakib Ribbon Studio (Overlays & Effects), Metadata Studio Pro v7.0 (Stock Tools, অপরিবর্তিত)।
- প্রতিটা ভিজ্যুয়াল টুলে: প্রিভিউ প্যানেলে মাউস নিলে/ক্লিক করলে চারপাশে ঘুরন্ত গ্লো লাইন।
- ডাউনলোড এখন একটা ছোট "⬇ Export" ড্রপডাউনে: ফরম্যাট (PNG/JPG/SVG/EPS), ZIP/প্যাক, আর Collection।
- Collection: "＋ Add this design" দিয়ে যত খুশি ডিজাইন জমানো যায় (সব টুল মিলিয়ে)। ডাউনলোডে ফরম্যাট বেছে নেওয়া যায়, একটা ZIP আসে।
- SVG: গ্রেডিয়েন্ট ডুপ্লিকেট কমানো, সংখ্যা ছোট করা, লেয়ার ক্লিন-আপ (v1.0.1 থেকে চলমান)।

v1.0.3 পরিবর্তন:
- সরানো হয়েছে: পুরনো Metadata Generator Pro। এর জায়গায় Metadata Studio Pro (আপনার ফাইনাল "Best Metadata pro" ফাইল, অপরিবর্তিত)।
- নতুন: Adobe Stock Intelligence (Stock), Image to Master Prompt Studio ও Sakib AI Chat Studio (Prompt Tools), Sakib Light FX Studio (Overlays & Effects), Sakib Creative PRO (Backgrounds)।
- Collection এখন Export মেনুর বাইরে: "⬇ Export" (শুধু ডাউনলোড), "＋ Collection" (ডিজাইন জমা, উড়ে গিয়ে Batch-এ পড়ে), "📦 Batch" (খুললে অ্যানিমেশনসহ জিজ্ঞেস করে PNG / JPG / SVG / EPS কোনটা নামাবেন)।
- Image to Master Prompt-এ বন্ধ হয়ে যাওয়া Gemini 1.5 / 2.0 / 3.1 মডেল বাদ, Gemini 3.8 Flash এখন প্রথমে।

v1.0.4 পরিবর্তন:
- নতুন টুল: AquaDrop Studio, Film Dust Studio (Overlays & Effects), Starburst Studio (Backgrounds), Motif Loom (Patterns), Grass Studio (নতুন টপিক: Nature & Scenery, সাথে Vector Landscape)।
- AquaDrop-এ নতুন Export/Collection/Batch বাটন। Motif Loom-এ নিজের Collection ও Export আগের মতোই আছে।
- পুরো সাইট এখন পাসওয়ার্ড-লকড (এনক্রিপ্টেড)। লক ছাড়া ভেতরের কিছু দেখা যায় না।

v1.0.5 পরিবর্তন:
- Export ড্রপডাউন সরানো হয়েছে। PNG, JPG, SVG, EPS এখন সরাসরি টুলবারে। ZIP/প্যাক বাটন "🗜 ZIP" মেনুতে।
- ＋ Collection শুধু ডিজাইন জমা করে। 📦 Batch খুললে আগের মতোই ফরম্যাট বাছার পপআপ আসে।
- সাইটের পাসওয়ার্ড বদলানো হয়েছে।
