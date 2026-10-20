# Rayhan AI — নতুন ফিচার (v14)

## 🐍 কোড ইন্টারপ্রেটার
- টুলবক্স → **কোড ইন্টারপ্রেটার**
- ব্রাউজারেই Python চলে (Pyodide, প্রথমবার ~10MB)
- Excel/CSV ধরনের হিসাব, লুপ, numpy/pandas (প্যাকেজ ইনস্টল বাটন)
- AI দিয়ে কোড লেখার বাটন আছে

## 🌐 এক ক্লিকে ওয়েবসাইট লাইভ
1. Settings / টুলবক্স → **ওয়েবসাইট লাইভ** থেকে Netlify Personal Access Token সেভ করুন  
   (https://app.netlify.com/user/applications#personal-access-tokens)
2. **🛠 Build app** চালু করে গেম/অ্যাপ বানান
3. AI HTML দিলে চ্যাটে বা Preview-তে **🌐 Live** চাপুন
4. পাবলিক HTTPS লিংক পাবেন

## 📱 APK (ফোনে ইনস্টল)
Build মোডে HTML গেম/অ্যাপ এলে এখন বাটনগুলো:
- ▶ Preview / Test
- 🔍 Review & Fix
- ⬇ HTML
- **📱 APK** ← নতুন
- **🌐 Live** ← নতুন

**📱 APK** চাপলে Android Studio-রেডি প্রজেক্ট ZIP ডাউনলোড হয় (`*-apk-project.zip`):
- WebView অ্যাপ + আপনার HTML `assets/index.html`-এ
- README-APK.txt-এ ধাপে ধাপে নির্দেশনা
- Android Studio দিয়ে APK বানিয়ে ফোনে ইনস্টল করুন

> ব্রাউজার থেকে সরাসরি সাইন করা `.apk` ফাইল জেনারেট করা সম্ভব নয় (Google/Android নিরাপত্তা)। তাই সম্পূর্ণ সোর্স প্রজেক্ট দেওয়া হয়েছে যাতে আসল ইনস্টলযোগ্য APK তৈরি হয়।

## ফাইল তালিকা
- index.html (আপডেটেড)
- config.js, manifest.json, sw.js, icon-192.png, icon-512.png
- README-SETUP.md, README-NEW-FEATURES.md
