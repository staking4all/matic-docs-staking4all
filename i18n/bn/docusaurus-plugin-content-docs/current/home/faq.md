---
id: faq
title: FAQ
description: Polygon সম্পর্কিত FAQ
keywords:
  - docs
  - matic
  - polygon
  - faq
image: https://wiki.polygon.technology/img/polygon-wiki.png
---

# প্রায়শই জিজ্ঞাসিত প্রশ্নাবলী {#frequently-asked-questions}

## Polygon কী? {#what-is-polygon}

Polygon হল পাবলিক ব্লকচেইনের জন্য একটি স্কেলিং সমাধান, বিশেষ করে Ethereum। Polygon একটি সুরক্ষিত এবং বিকেন্দ্রীভূত পদ্ধতিতে একটি উচ্চতর ব্যবহারকারী অভিজ্ঞতা নিশ্চিত করার সময় স্কেলেবিলিটি প্রদান করে। এটি Kovan Testnet-এ Ethereum এর জন্য একটি কার্যক্ষম বাস্তবায়ন আছে। Polygon ভবিষ্যতে অন্যান্য ব্লকচেইনের সমর্থন করতে চায় যা আমাদের বিদ্যমান পাবলিক ব্লকচেইন নেটওয়ার্কে স্কেলেবিলিটি প্রদানের পাশাপাশি interoperability বৈশিষ্ট্য সরবরাহ করতে সক্ষম করবে।

## Plasma-এর অন্যান্য ইমপ্লিমেন্টেশন থেকে Polygon-এর পার্থক্য কী কী? {#how-is-polygon-different-from-other-implementations-of-plasma}

Polygon-এর Plasma-এর ইমপ্লিমেন্টেশন EVM-এ পরিচালিত স্টেট-ভিত্তিক সাইডচেইন দিয়ে নির্মিত, যেখানে Plasma-এর অন্যান্য ইমপ্লিমেন্টেশন মূলত UTXO ব্যবহার করে যা তাদের শুধু পেমেন্টের মধ্যে সীমাবদ্ধ করে দেয়। স্টেট-ভিত্তিক সাইডচেইনের ফলে Polygon সাধারণ স্মার্ট চুক্তিগুলিতেও স্কেলেবিলিটি সুবিধা প্রদান করতে পারে।

দ্বিতীয়ত, Polygon একটি পাবলিক চেকপয়েন্ট লেয়ার ব্যবহার করে যা পর্যায়ক্রমিক অন্তর পরে চেকপয়েন্ট প্রকাশ করে (প্লাজমা ক্যাশে প্রতিটি ব্লকের পরে চেকপয়েন্ট অসদৃশ) (প্লাজমা ক্যাশে প্রতিটি ব্লকের পর চেকপয়েন্ট প্রকাশ করে) যা sidechains হাই স্পিনে কাজ করতে পারে, এবং ব্যাচে চেকপয়েন্ট প্রকাশ করার সময় sidechains হাই স্পিনে কাজ করতে পারে। এই চেকপয়েন্টগুলির পাশাপাশি প্রতারণা প্রতিরোধী সিস্টেমের সাহায্যে Polygon-এর সাইডচেইনগুলি নিরাপদে কার্য পরিচালনা করতে সক্ষম হবে।

## আপনাদের প্রজেক্ট Plasma চেইন ব্যবহার করে Ethereum-কে স্কেলেবিলিটি প্রদান করে, তাহলে এটি কি কোনো প্রোটোকল নাকি এটি নিজেই একটি ব্লকচেইন? {#your-project-provides-scalability-for-ethereum-using-plasma-chains-is-it-a-protocol-or-a-native-blockchain-in-itself}

Polygon নেটওয়ার্ক একটি **"sidechain"** সমাধান যেখানে Ethereum প্রধান চেইন সম্পদ, অর্থাৎ প্রধান চেইনের সমস্ত dApps / Token/Protocols স্থানান্তরিত / Polygon sidechain(s) এ স্থানান্তরিত করা যেতে পারে এবং প্রয়োজন হলে, কেউ মূল চেইনে ফিরে আসবে এমন একটি সম্পদ প্রত্যাহার করতে পারেন।

## অন্যান্য প্রতিযোগীদের তুলনায় Polygon-এর সুবিধা কী কী? {#what-are-the-competitive-advantages-of-polygon-over-its-competitors}

### L2 স্কেলিং সমাধান {#l2-scaling-solutions}

Polygon ডিসেন্ট্রাইলেজশন দিয়ে স্কেল অর্জনের জন্য প্রতিশ্রুতিবদ্ধ। Polygon পর্যায়ক্রমিক চেকপয়েন্ট এবং প্রতারণা প্রতিরোধী সিস্টেম ব্যবহার করে। ব্যবহারকারীগণ তাদের এসেট উইথড্র করতে চাইলে, তারা চেকপয়েন্টগুলি ব্যবহার করে প্রমাণ করে যে সাইডচেইনে তাদের এসেট আছে এবং প্রতারণা প্রতিরোধী সিস্টেম ব্যবহার করে যেকোনো প্রতারণা বা অন্য কোনো অবৈধ কার্য ও স্ল্যাশ স্ট্যাকার প্রতিরোধ করা হয়।

অন্যান্য প্রকল্পগুলিও L2 স্কেলিং সমাধান দিচ্ছেন তবে আমরা দুটি কী উপাদান থাকি:

1. প্রথমত, Polygon শুধু আর্থিক লেনদেনের জন্য নয়, গেম এবং অন্যান্য ইউটিলিটি dApps এ ফোকাস করছে। আমাদের আছে ঋণ/ট্রেডিং dApps (টোকেন সোয়াপ, মার্জিন ট্রেড, এবং আরও অনেক কিছু) মতো full-blown আর্থিক পরিষেবাটির জন্য প্ল্যান আছে।

2. দ্বিতীয়ত, Polygon চেকপয়েন্টের জন্য 1-সেকেন্ড সময়ের ব্লক (PoS লেয়ার সহ) ব্যবহার করে। কিন্তু, অন্যান্য অনেক সিস্টেমেরই Ethereum ব্লকের সময়ের চেয়েও বেশি সময়ের প্রয়োজন হতে পারে, কারণ তাদের সাইডচেইনের প্রতিটি ব্লককে মেইনচেইনে পাঠানোর প্রয়োজন হয়ে থাকে।

### L1 স্কেলিং সমাধান {#l1-scaling-solutions}

তাছাড়া, অন্যান্য সকল স্কেলিং প্রজেক্টের তুলনায় Polygon এগিয়ে রয়েছে কারণ এটি খুবই ভালো মানের ডিসেন্ট্রাইলেজশন সুবিধা প্রদান বজায় রাখার পাশাপাশি স্কেলও করতে পারে।

আরো গুরুত্বপূর্ণ, এই স্কেলেবিলিটি প্রকল্পে একটি "হুইল পুনর্গঠন" সমস্যা আছে। তারা নতুন ব্লকচেইন তৈরি করছে যেখানে ডেভেলপার কমিউনিটি, প্রোডাক্ট ইকোসিস্টেম, টেকনিক্যাল ডকুমেন্টেশন এবং ব্যবসার **"স্ক্র্যাচ"** থেকে তৈরি করা প্রয়োজন। অন্যদিকে, Polygon, একটি EVM-enabled চেইনে এবং Ethereum মেইন চেইনে তৈরি সমস্ত dApps / assets একটি বোতামের ক্লিকে উপলব্ধ স্কেলেবিলিটি সহ রয়েছে।

### পেমেন্ট {#payments}

আমরা বিশ্বাস করি যে ব্যবহারযোগ্যতার দিক থেকে Polygon এগিয়ে রয়েছে কারণ অন্যান্য সিস্টেমে প্রেরক এবং প্রাপক উভয়কেই তাদের পেমেন্ট চ্যানেল তৈরি করতে হয়। বেশিরভাগক্ষেত্রেই, এটি ব্যবহারকারীদের জন্য খুবই শ্রমসাধ্য ব্যাপার হয়ে উঠে। কিন্তু Polygon প্রযুক্তিতে ব্যবহারকারীদের পেমেন্ট চ্যানেল থাকার কোনো বাধ্যবাধকতা নেই। তাদের শুধুমাত্র বৈধ Ethereum অ্যাড্রেস টোকেন থাকলেই হবে। এটি আমাদের ডিসেন্ট্রালাইজড অ্যাপ্লিকেশনের ব্যবহারকারীর অভিজ্ঞতাকে উন্নত করার দীর্ঘমেয়াদী পরিকল্পনারও একটি অংশ।

### ট্রেডিং এবং ফাইন্যান্স {#trading-and-finance}

Polygon তার প্ল্যাটফর্মে DEX's (eg. 0x), লিকুইডিটি পুল (eg. Kyber Network) এবং অন্যান্য ধরনের আর্থিক প্রোটোকল যেমন Lending প্রোটোকল সক্ষম করতে চায়, যা Polygon ব্যবহারকারীদের DEXs, Lending dApps, LPs এবং আরও অনেক কিছু মত বিভিন্ন আর্থিক varied অ্যাপ্লিকেশন অ্যাক্সেস করতে পারবে।

## অন্যান্য সাইডচেইন সমাধানের তুলনায় Polygon-এর অবস্থান কেমন? {#how-does-polygon-compare-with-other-sidechain-solutions}

Polygon-এ, সকল সাইড লেনদেন সাইডচেইনের পাশাপাশি মেইনচেইনেও একাধিক মেকানিজম দিয়ে সুরক্ষিত করা হয়। On ব্লক প্রযোজক লেয়ারের যে কোন লেনদেন যাচাই করা হয় এবং একটি অত্যন্ত বিকেন্দ্রীভূত চেকপয়েন্ট লেয়ারের দ্বারা প্রধান চেইনে চেকপয়েন্ট করা sidechain,

সাইডচেইনে কোনো প্রতারণামূলক করা হলে, তা চেকপয়েন্টিং লেয়ার দিয়ে শনাক্ত ও যথাযথ পদক্ষেপ গ্রহণ করা হবে। এমনকি চরম এবং অত্যন্ত অসম্ভাব্য দৃশ্যকল্প যেখানে ব্লক প্রযোজক layer  এবং চেকপয়েন্ট layer  উভয়ই কোলাড, তবুও প্রধান চেইনে জালিয়াতি প্রমাণ রয়েছে, যার উপর জনতার যে কেউ আস, ে এবং sidechain. জালিয়াতি দি, ে যে কোন লেনদেনটি চ্যালেঞ্জ করতে পারে।

যদি চ্যালেঞ্জটি সফল is ে, তাহলে colluding পার্টির জন্য একটি বিশাল অর্থনৈতিক বিখ্যাত/আর্থিক শাস্তি আছে কারণ তাদের স্টেক স্ল্যাশ করা হয়েছে। এছাড়াও, যে পাবলিক চ্যালেঞ্জার করেছেলিনে তাকে প্রতারণামূলক সাইডচেইন পক্ষদের স্ল্যাশ করা স্ট্যাক দিয়ে পুরস্কৃত করা হবে।

এর ফলে Polygon একটি অর্থনৈতিকভাবে প্রণোদনামূলক সাইডচেইন নেটওয়ার্ক হিসেবে প্রতিষ্ঠিত করেছে যা সাইডচেইন লেনদেনের ক্ষেত্রে এই সিস্টেমটিকে উচ্চমাত্রার ডিসেন্ট্রালাইজড এবং সুরক্ষিত সিস্টেমে পরিণত করেছে।

এছাড়াও, Polygon সাইডচেইনের ধারণক্ষমতা ও টিপিএস অন্যান্য সমাধানের তুলনায় অনেক বেশি। কারণ Polygon-এ একসাথে হাজার হাজার লেনদেন করা যাবে, যেখানে অন্যরা একক সাইডচেইন হিসেবে কাজ করে থাকে। ফলে তাদের শুধুমাত্র কয়েক হাজার লেনদেনের সীমাবদ্ধতা রয়েছে।

## কোন নীতিমালা অনুসারে নতুন সাইডচেইন যোগ করা হবে? প্রাইভেট কোম্পানিগুলির স্থানীয় সাইডচেইনের জন্য কোনো বিশেষ প্রয়োজনীয়তা কি রয়েছে? {#via-what-principles-will-new-sidechains-be-added-will-there-be-any-special-requirements-for-private-companies-local-sidechains}

স্টেট চ্যানেলগুলির তুলনায় Plasma স্কেলিং ফ্রেমওয়ার্কের ক্ষেত্রে আরো ভালো একটি বিকল্প প্রদান করে, কারণ ফ্রেমওয়ার্কটি দ্বারা নিরাপত্তার নিশ্চয়তা পাওয়া যায় - মানে হচ্ছে কখনই কোনো উপায়েই ব্যবহারকারীগণ তাদের অর্থ হারাবেন না। অবশ্যই, অর্থ ফেরত পেতে কিছুটা বিলম্ব হতে পারে কারণ Byzantine Plasma অপারেটর শূন্য থেকে টাকা তৈরি বা একই লেনদেনের জন্য দুইবার খরচ করতে পারে না।

Polygon ভবিষ্যতে সম্পূর্ণ উন্মুক্ত এবং পাবলিক ব্লকচেইন অবকাঠামোতে পরিণত হওয়ার যথাসাধ্য চেষ্টা করবে। সেই ব্যবস্থায় অর্থনৈতিক প্রণোদনা/শাস্তিই মূলত সিস্টেমের নিরাপত্তা ও স্থিতিশীলতা বজায় রাখবে। তাই যেকেউ সিস্টেমটিতে যোগ দিতে পারবে এবং কনসেনসাসে অংশগ্রহণ করতে পারবে। নেটওয়ার্ক সিডিং পর্যায়ে সাইডচেইন সক্ষম করতে প্রাথমিকভাবে Polygon-কে একটি বড় ভূমিকা পালন করতে হবে।

এছাড়াও, প্রাথমিকভাবে Polygon একটি পাবলিক সাইডচেইন, অর্থাৎ অন্য সব পাবলিক ব্লকচেইনের মতই সবার জন্য উন্মুক্ত সাইডচেইন হিসেবে কাজ করবে। তবে, এন্টারপ্রাইজ Polygon চেইন নির্দিষ্ট কিছু প্রতিষ্ঠানের জন্য আলাদা সাইডচেইন (অ-গোপনীয়তা সক্ষম) প্রদান করার ব্যাপারে আশা ব্যক্ত করছে। মেইন চেইনে চেকপয়েন্টিং লেয়ার এবং প্রতারণা প্রতিরোধী সিস্টেম ব্যবহার করে সেই চেইনগুলির নিরাপত্তা এবং ডিসেন্ট্রালাইজেশন এখনো কার্যকরা রাখা হবে।

## সাইডচেইন কি মেইনচেইনের (Ethereum) সাথে সিঙ্ক করা হবে? {#will-sidechains-also-be-synced-with-the-main-chain-ethereum}

জ্বি, অবশ্যই। সাইডচেইনে সম্পন্ন হওয়া সকল লেনদেনকে যাচাই করার জন্য পাবলিক চেকপয়েন্টিং লেয়ার ব্যবহার করা হবে এবং মেইনচেইনে তার প্রমাণ প্রকাশ করা হবে। সাইডচেইন লেনদেনের পূর্ণাঙ্গ নিরাপত্তা নিশ্চিত করার জন্য মেইনচেইন Plasma চুক্তিতে বিভিন্ন প্রকারের প্রতারণা প্রতিরোধী সিস্টেম অন্তর্ভুক্ত রয়েছে, যা দ্বারা প্রতারণামূলক কার্যকলাপের জন্য যেকোনো সাইডচেইন লেনদেনকে চ্যালেঞ্জ করা যাবে। যদি কোনো চ্যালেঞ্জার সফল হন, তাহলে প্রতারণায় জড়িত সাইডচেইন পক্ষের স্ট্যাক স্ল্যাশ করা হবে এবং তা চ্যালেঞ্জারের কাছে স্থানান্তর করা হবে। এটি সদা চলমান উচ্চ স্ট্যাকের বাগ বাউন্টির সমতুল্য। আরো ভালোভাবে বোঝার জন্য নিচে একটি ডায়াগ্রাম দেয়া হয়েছে:

![স্ক্রিনশট](/img/matic/Architecture.png)

## হোয়াইট পেপারের শেষে "সম্ভাব্য ব্যবহার ক্ষেত্র" নামে একটি তালিকা রয়েছে - সবগুলোই কি বাস্তবায়ন করা হবে? যদি তা করা হয়, তাহলে কোনটি আগে করা হবে? {#at-the-end-of-the-white-paper-there-is-a-list-of-potential-use-cases-will-all-of-that-be-implemented-in-what-order}

মৌলিক লজিক হল - যদি একটি dApp / প্রোটোকল থাকে তবে এটি Ethereum-এ কাজ করছে, তবে এটি কম লেনদেনের throughput এবং উচ্চ লেনদেনের ফি দ্বারা সীমাবদ্ধ - তাহলে আমরা Polygon নেটওয়ার্কে এই dApps / Protocols এর জন্য সমর্থন যোগ করতে সক্ষম হবে।

## Polygon-এর Plasma ইমপ্লিমেন্টেশন কপি করা কী কারণে কঠিন হতে পারে? {#why-will-it-be-difficult-to-replicate-polygon-s-plasma-implementation}

যদিও এটি নেটওয়ার্কের প্রভাবের বিষয়ে বেশি আছে যার মধ্যে নেটওয়ার্ক অন্যদের চেয়ে ভাল ইকোসিস্টেম স্কেল / grow ে সক্ষম হয়, তবে ব্লকচেইন সমাধানটি অবশ্যই ওপেন সোর্স হতে হবে কারণ তাদের দ্বারা ব্যবহৃত প্রকৃত সম্পদ নিয়ে গঠিত।

সকল উন্মুক্ত প্রজেক্টের ক্ষেত্রেই এই বিষয়টি প্রযোজ্য। এটি আমাদের ক্ষেত্রেও অন্যান্য প্রতিদ্বন্দ্বীদের মতই সমভাবে প্রযোজ্য কারণ আমরা অচিরেই আমাদের GPL লাইসেন্স পেতে যাচ্ছি যা আমাদের ইমপ্লিমেন্টেশন ব্যবহারকারী সবাইকেই তাদের কোড উন্মুক্ত করার বিষয়ে বাধ্যবাধকতা আরোপ করে। তাছাড়া, Bitcoin, Ethereum এবং অন্য সব প্রজেক্টেও কপি করা হয়ে থাকে, কারণ একটি প্রজেক্ট কতটা এগিয়ে যাবে তা মূলত নেটওয়ার্ক ইফেক্টের উপর নির্ভরশীল।

## Polygon নেটওয়ার্কের Plasma ইমপ্লিমেন্টেশনে বিশেষ কী কী সুবিধা রয়েছে? {#what-s-special-about-polygon-network-s-plasma-implementation}

Polygon Plasma UTXO সিস্টেমের পরিবর্তে একটি অ্যাকাউন্ট-ভিত্তিক মডেল সিস্টেম ব্যবহার করে থাকে। এতে আমরা Polygon চেইনে EVM ব্যবহার করার একটি বিশাল সুবিধা পেয়ে থাকি, যা আমাদের Polygon নেটওয়ার্কে সম্পূর্ণ Ethereum ইকোসিস্টেম, ডেভেলপার টুলস, ইন্টিগ্রেশন লাইব্রেরি ইত্যাদি ব্যবহার করার সুবিধা প্রদান করে।

dApps-এর ERC20 টোকেনে কোনো পরিবর্তন না করেই Polygon নেটওয়ার্কটিতে সেগুলি ব্যবহার করা যেতে পারে। এছাড়াও, আমাদের চেকপয়েন্টিং লেয়ার দিয়ে আমরা অন্যান্য Plasma ইমপ্লিমেন্টেশনের তুলনায় অনেক দ্রুত কাজ করতে পারি, কারণ আমরা সকল ব্লকের প্রমাণকে ব্যাচ করে ফেলি, অন্যদিকে বাকি সব Plasma ইমপ্লিমেন্টেশনকে প্রতিটি ব্লকের প্রমাণকে বাধ্যতামূলকভাবে মেইনচেইনে জমা দিয়ে থাকে।

## আপনারা সেন্ট্রালাইজেশনের সমস্যাগুলিকে কীভাবে সমাধান করবেন? {#how-are-you-going-to-solve-the-issues-with-centralization}

এই বিষয়ে আরো বিস্তারিত জানতে নিচের ডায়াগ্রামটি দেখুন:

![স্ক্রিনশট](/img/matic/Merkle.png)

প্রথমত, PoA নোডগুলিকে ডেলিগেট করা হবে (স্বচ্ছলতার প্রমাণ দিয়ে অর্থাৎ, তাদের উচ্চ পরিমাণ স্ট্যাক ডিপোজিট করতে হবে) এবং EOS স্টাইলের ডেলিগেটেড প্রুফ অফ স্ট্যাক (DPoS) বা ডেলিগেটেড Byzantine ফল্ট টলারেন্স (DBFT) নোডের মতই PoS লেয়ার দ্বারাই মূলত KYC নির্বাচিত হয়ে থাকে।

দ্বিতীয়ত, মনে করা যাক সকল ডেলিগেটগণই (বা 2/3 অংশ) দুর্নীতিগ্রস্ত হয়ে গেল এবং ত্রুটিপূর্ণ ব্লক তৈরি করছে। এই ক্ষেত্রে PoSo লেয়ার স্ট্যাকারগণ সকল ব্লককে যাচাই করবে এবং যদি কোনো প্রতারণা লক্ষ্য করা হয়, তবে ডেলিগেটের স্ট্যাক স্ল্যাশ করা হবে এবং সংশোধনীমূলক পদক্ষেপ হিসেবে তার চেকপয়েন্টিং বন্ধ করে দেয়া হবে।

তৃতীয়ত, মনে করা যাক স্ট্যাকার PoS লেয়ারও (যা সাধারণত অনেক বড় সংখ্যক নোড হয়ে থাকে) দূর্নীতিগ্রস্ত হয়ে গেল এবং ত্রুটিপূর্ণ চেকপয়েন্ট তৈরি করছে অর্থাৎ, সকল PoA এবং PoS ত্রুটিপূর্ণ। সেইরকম ক্ষেত্রেও Plasma দর্শন অনুসারে, আমরা সাইডচেইন স্কেলিং-এর অন্যতম জনপ্রিয় বিষয়বস্তু**প্রতারণা প্রতিরোধী সিস্টেম** ব্যবহার করি যা দিয়ে অনেক বড় প্রজেক্টেও পর্যবেক্ষণ করা হয়েছে (পর্যবেক্ষণকারীদের GitHub-এ আমাদের রিপোজিটরি পর্যবেক্ষণকারী হিসেবে গণ্য করা হবে)। এই প্রতারণা প্রতিরোধী মেকানিজমটি দিয়ে যেকেউ মেইনচেইনে, Ethereum-এ যেকোনো লেনদেনকে চ্যালেঞ্জ করতে পারবেন।

## কেন MATIC টোকেনের প্রয়োজন হয়? {#why-is-matic-token-required}

নিম্নলিখিত কারণগুলো ম্যাটিক টোকেন থাকার প্রয়োজন শক্তিশালী করে:

### Polygon পাবলিক ব্লকচেইনের জন্য একটি সাধারণ উদ্দেশ্য স্কেলিং সমাধান হতে চায় {#polygon-intends-to-be-a-general-purpose-scaling-solution-for-public-blockchains}

আমরা বেইসচেইন হিসেবে Ethereum দিয়ে আমাদের যাত্রা শুরু করছি, তবে ভবিষ্যতে আরো অনেক বেইসচেইনে Polygon বিস্তৃত করা হতে পারে। শীঘ্রই আরো অন্যান্য বেইসচেইন যোগ করা হবে, কারণ সাইডচেইনে শুধুমাত্র একটি মুদ্রা (ether) ব্যবহার করে ফি প্রদানের কোনোই মানে হয় না। যদি কোনো বেইসচেইনের ভবিষ্যতে অস্তিত্ব সংক্রান্ত উদ্বেগ থাকে এবং সেই বেইসচেইনের মুদ্রাকে Polygon-এর নেটিভ এসেট হিসেবে গ্রহণ করা হয়, তবে তা স্কেলিং নেটওয়ার্ককে অকার্যকর করে তুলবে। তাই, Polygon-এর নিজস্ব নেটওয়ার্ক টোকেনে স্ট্যাকার ইকোসিস্টেম তৈরি করা অত্যন্ত গুরুত্বপূর্ণ।

### Appcoin নিরাপত্তা মডেল {#appcoin-security-model}

Polygon Kyber-এর মত একটি লিকুইডিটি পুল ব্যবহার করে টোকেন সোয়াপ মেকানিজমের মাধ্যমে Dapp-coins দিয়ে Polygon ফি প্রদানের জন্য Dapps চালু করার ব্যাপারে আশাবাদী। ব্যবহারকারী কেবল ফিতে দিতে তার dApp-coins ব্যবহার করে, ব্যাকগ্রাউন্ডে dApp-coin MATIC টোকেন জন্য swapped করা হয়। সুতরাং, নিরবচ্ছিন্ন ব্যবহারকারীর অভিজ্ঞতা প্রদান করতে ইচ্ছুক DApp ডেভেলপারগণ Polygon লিকুইডিটি পুল পরিচালনার ক্ষেত্রে সহায়তা করবে।

### nascent পর্যায়ে নেটওয়ার্ক সিডিং {#seeding-the-network-in-nascent-stages}

যদি শুরুতে নেটওয়ার্কে একবারে কম বা শুন্য লেনদেন হয়, তবে সিস্টেমটিকে সিড করা আমাদের জন্য অত্যন্ত কষ্টসাধ্য হয়ে উঠবে, কারণ Eth-কে উচ্চমাত্রার ডিসেন্ট্রালাইজড যাচাইকারী লেয়ার এবং ব্লক প্রডিউসারদের কাছে ডিস্ট্রিবিউট করতে আমরা সক্ষম নই। তবে Matic টোকেন দিয়ে আমরা সিড করা ব্লক প্রডিউসারদের টোকেনের একটি বড় অংশ, চেকপয়েন্টার স্ট্যাক প্রদানের পাশাপাশি ব্লক পুরস্কারও দেয়া হবে। এই বিধানটি নিশ্চিত করে যে নেটওয়ার্ক ইফেক্ট শুরু হতে কিছু সময় নিলেও স্ট্যাকারের পুরস্কার পেতে থাকবেন। অনেকেরই মনে হতে পারে যে শুধু Bitcoin দিয়েই কেন ব্লকে মাইনিং পুরস্কার দেয়া হয়, কারণ নেটওয়ার্কটিকে সুরক্ষিত রাখতে এই উপায়ে স্ট্যাকার এবং ব্লক প্রডিউসারদের প্রণোদনা প্রদান করা যায়।

যদি আপনার ডেভ সংক্রান্ত কোনো প্রশ্ন থাকে, তবে জানুন আমাদের অন্যতম কৌশল হচ্ছে সহজেই যেন ডেভেলাপার করতে পারে সে বিষয়টি নিশ্চিত করা। প্রথম থেকেই Polygon-এ সকল Ethereum ডেভ টুল কাজ করার বিষয়টিকে আমরা নিশ্চিত করেছি। টেস্টনেটে ফি প্রদানের জন্য প্রয়োজনীয় টোকেনের ক্ষেত্রে ডেভেলাপারগণ Ethereum-এর মত সিস্টেম ব্যবহার করেই তা করতে পারবেন। ডেভ Ethereum-এর মতই Polygon ফসেট থেকে টেস্টনেটের জন্য বিনামূল্যে টোকেন পাবেন। আপনি শুধুমাত্র যখন Polygon Mainnet-এ deploy  করতে চান তখন আপনাকে MATIC টোকেন প্রয়োজন, যেখানে Gas fee Ethereum-এর চেয়ে অনেক কম, আপনি Ethereum-এ পাবেন এমন একটি লেনদেনের ফি এর 1/100th কাছাকাছি আপনি Gas fee এ পাবেন

## MATIC টোকেনের ব্যবহার এবং চাহিদা কী দিয়ে পরিচালিত হয়? {#what-drives-the-use-and-demand-for-matic-tokens}

টোকেনের দুটি প্রাথমিক ব্যবহার রয়েছে:

1. নেটওয়ার্কে লেনদেনের ফি প্রদানের জন্য টোকেন ব্যবহার করা হয়ে থাকে।
2. চেকপয়েন্টিং লেয়ার এবং ব্লক প্রোডাকশন লেয়ারের জন্য প্রুফ অফ স্ট্যাক কনসেনসাস মেকানিজমে অংশগ্রহণ করার জন্য টোকেন ব্যবহার করে স্ট্যাক করা হয়।

### টোকেন ডিম্বাণু জন্য কিছু সেকেন্ডারি কারণ {#some-of-the-secondary-reasons-for-token-demand}

* Polygon নেটওয়ার্ক Kyber-এর মত একটি লিকুইডিটি পুল ব্যবহার করে টোকেন সোয়াপ মেকানিজমের মাধ্যমে Dapp-coins দিয়ে Polygon ফি প্রদানের জন্য Dapps চালু করার ব্যাপারে আশাবাদী। ব্যবহারকারী কেবল ফিতে দিতে তার dApp-coins ব্যবহার করে, ব্যাকগ্রাউন্ডে dApp-coin MATIC টোকেন জন্য swapped করা হয়। সুতরাং, নিরবচ্ছিন্ন ব্যবহারকারীর অভিজ্ঞতা প্রদান করতে ইচ্ছুক DApp ডেভেলপারগণ Polygon লিকুইডিটি পুল পরিচালনার ক্ষেত্রে সহায়তা করবে।

* দ্রুত প্রস্থান সক্ষম করতে আমরা ধর্মকে প্রোটোকল ব্যবহার করে একটি ঋণ lending বাস্তবায়ন করছি যেখানে একজন আন্ডাররাইট/ল্যান্ডার প্রস্থান থেকে বের হতে পারেন এবং স্বার্থে একটি ছোট ফি দিয়ে প্রস্থান পরিমাণ বিতরণ করতে পারেন। এক সপ্তাহ পরে ঋণদাতা প্রস্থান-টোকেন ব্যবহার করে টোকেন ক্লেইম করতে পারবেন। এই উপায়ে ব্যবহারকারী প্রায় সঙ্গে সঙ্গেই উইথড্র করতে পারেন, আবার ঋণদাতা তার প্রদানকৃত পরিষেবার জন্য মুনাফাও লাভ করতে থাকেন।

### প্রোটোকল লেভেলে টোকেন বার্ন করা {#protocol-level-burning-of-tokens}

আমরা প্রতিটি ব্লকে লেনদেনে কিছুটা অংশ বার্ন করতে চাই। এটি টোকেনগুলিকে মুদ্রাসংকোচন প্রকৃতির করে গড়ে তুলে এবং প্রোটোকল লেভেলে মূল্যের পরিপ্রেক্ষিতে সেগুলিকে কনস্ট্যান্ট সাপোর্ট প্রদান করে।

### সহজ এন্ট্রি (তাই এটি দ্রুত গ্রহণের সম্ভাবনা অত্যন্ত প্রবল) {#low-entry-barrier-and-hence-higher-chances-of-quick-adoption}

শেষ-ব্যবহারকারীদের গ্রহণের জন্য আমরা ব্যাপকভাবে DApps ব্যবহার করতে পারি। মূল বৈশিষ্ট্যগুলির মধ্যে একটি হল যে আমরা একটি আর্কিটেকচার বজায় রাখি যা Ethereum ডেভেলপমেন্ট ইকোসিস্টেমের জন্য সম্পূর্ণরূপে সামঞ্জস্যপূর্ণ i.e, যার মধ্যে সমস্ত স্মার্ট কন্ট্র্যাক্ট, ওয়ালেট, আইডিই, DevOps টুলস ইত্যাদি সরাসরি Polygon এর সাথে সামঞ্জস্যপূর্ণ রয়েছে।

যেকোনো Ethereum Dapp প্রায় কোনো উল্লেখযোগ্য পরিবর্তন না করেই Polygon-এ পোর্ট করা যেতে পারে। তাই Polygon এ স্থানান্তরিত থাকা বিদ্যমান Ethereum ডেভেলপারদের জন্য এন্ট্রি বাধা নগণ্য যা একটি ভাইরাল dApp গ্রহণ শুরু করতে পারে। এই নেটওয়ার্কে বহুভুজ নেটওয়ার্কের চারপাশে তৈরি হওয়া নেটওয়ার্ক প্রভাবের কারণে অনেক জৈব চাহিদা to া সম্ভব।

## টোকেন টাইপ কি ERC20? {#is-token-type-erc20}

হ্যাঁ। এবং একই টোকেন বহুভুজ চেইনে প্রযোজ্য হবে অর্থাৎ ভবিষ্যতে একটি নেটিভ টোকেনে যাওয়ার দরকার নেই।

## আপনি Ethereum নেটওয়ার্কে কী পরিমাণ TPS নিয়ে আসতে পারবেন বলে মনে করছেন? আপনি এখন টেস্টনেটে কী চালাচ্ছেন? {#what-is-the-expected-tps-you-ll-be-able-to-bring-to-the-ethereum-network-what-are-you-running-at-now-on-testnet}

একটি একক সাইডচেইনে প্রতি সেকেন্ডে 7,000+ লেনদেন করা যাবে। Polygon-এ একাধিক সাইডচেইন যোগ করার ক্ষমতা রয়েছে। তবে বর্তমানে আমাদের লক্ষ্য হচ্ছে একটি সাইডচেইন দিয়ে নেটওয়ার্কটিকে স্থিতিশীল করা।
