SMART SELLER BD — মোবাইল PWA প্যাকেজ

ফাইলগুলো:
- index.html: অ্যাপের মূল স্ক্রিন ও ফিচার
- manifest.webmanifest: ফোনে ইনস্টল করার পরিচিতি
- sw.js: অনলাইনে প্রথমবার খোলার পর কিছু ফাইল ক্যাশ করে
- icon-192.png, icon-512.png: অ্যাপ আইকন

গুরুত্বপূর্ণ সীমাবদ্ধতা:
এটি এখনো প্রোটোটাইপ। ডেটা একই ফোনের ব্রাউজারের localStorage-এ থাকে।
এতে এখনো লগইন, ক্লাউড ব্যাকআপ, একাধিক ফোনে sync, বাস্তব সাবস্ক্রিপশন পেমেন্ট,
সার্ভার-সাইড নিরাপত্তা বা APK build নেই। বাস্তব কাস্টমার ডেটার জন্য ব্যবহার করার আগে
এসব ব্যবস্থা যোগ করতে হবে। মাসিক ৳১,০০০ মূল্য UI-তে দেখানো আছে; পেমেন্ট চালু নয়।

ফোন থেকে প্রকাশের সাধারণ পথ:
1. GitHub-এ লগইন করে নতুন public repository তৈরি করো, নাম দাও smart-seller-bd.
2. এই ZIP আনজিপ করে ভেতরের পাঁচটি ফাইল repository-র root-এ upload করো.
3. Repository > Settings > Pages > Build and deployment-এ গিয়ে Deploy from a branch বেছে নাও.
4. Branch হিসেবে main এবং folder হিসেবে /(root) বেছে Save করো.
5. প্রকাশ হলে GitHub Pages একটি https://...github.io/... লিংক দেখাবে.
6. সেই HTTPS লিংক Chrome-এ খোলো; মেনু (⋮) থেকে Install app বা Add to Home screen বেছে নাও.

নোট: GitHub-এর মেনুর নাম/অবস্থান বদলাতে পারে। HTTPS hosting ছাড়া PWA install/service worker সবসময় কাজ করবে না.
