Shakib Studio Hub: ফ্রি অনলাইন লিংকে তোলার ধাপ (GitHub Pages)
=================================================================
এই ফোল্ডারের সবগুলো ফাইল একসাথে আপলোড করতে হবে:
index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, icon-maskable-512.png

ধাপ ১: github.com-এ ফ্রি অ্যাকাউন্ট খুলুন (Chrome-এ। কঠিন লাগলে Chrome-এর মেনু থেকে "Desktop site" চালু করুন)।
ধাপ ২: ডান পাশের + চিহ্ন > New repository। নাম দিন সাধারণ কিছু, যেমন: mytools-2026
        Public বেছে নিন (ফ্রি Pages-এর জন্য Public লাগে)। Create repository চাপুন।
ধাপ ৩: "uploading an existing file" লিংকে চাপুন। ZIP আগে আনজিপ করে নিন, তারপর ৬টা ফাইলই সিলেক্ট করে আপলোড দিন।
        নিচে Commit changes চাপুন।
ধাপ ৪: Settings > Pages। Source: "Deploy from a branch"। Branch: main, ফোল্ডার: /(root)। Save চাপুন।
ধাপ ৫: ১-২ মিনিট পর ওই পেজেই লিংক দেখাবে: https://আপনারইউজারনেম.github.io/mytools-2026/
ধাপ ৬: Chrome-এ লিংক খুলুন। ⋮ মেনু > "Install app" বা "Add to Home screen"। হোম স্ক্রিনে অ্যাপের মতো আইকন হবে।

আপডেট করতে: নতুন index.html আপলোড করে একই নামে Replace করুন। কয়েক মিনিটে নতুন ভার্সন আসবে।

সতর্কতা:
- Repository Public, তাই ফাইলটা কেউ খুঁজে পেলে দেখতে পারে। ফাইলের ভেতরে কোনো API key লিখবেন না। টুলে বসানো API key শুধু আপনার ব্রাউজারে সেভ থাকে।
- লিংক আর রিপোর নাম কাউকে না দিলে সাধারণত কেউ খুঁজে পাবে না।
