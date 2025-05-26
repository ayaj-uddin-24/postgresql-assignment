# postgreSQL Questions

### 1. What is PostgreSQL?
PostgreSQL হলো একটি শক্তিশালী, ওপেন সোর্স রিলেশনাল ডেটাবেস ম্যানেজমেন্ট সিস্টেম (RDBMS), যা ডেটা সংরক্ষণ, পরিচালনা এবং বিশ্লেষণের কাজে ব্যবহার হয়। এটি একটি SQL ভাষা।

### 2. What is the purpose of a database schema in PostgreSQL?
একটি ডেটাবেসের মধ্যে বিভিন্ন টেবিলে ডাটা গুলো সুন্দরভাবে গুছিয়ে রাখার জন্য মূলত Schema ব্যবহার করা হয়। তাছাড়া টেবিলের ডাটা গুলোকে আরো শক্তিশালী এবং সুরক্ষিত করে তোলার জন্য schema  ব্যবহার করা হয়।

### 3. Explain the Primary Key and Foreign Key concepts in PostgreSQL.
একটি টেবিলের মধ্যে যখন অনেকগুলো ডাটা insert করা হয় প্রত্যেকটি ডেটার জন্য আলাদা আলাদা ID কিংবা username কিংবা Email সেট করার জন্য আমরা যেই keyword ব্যবহার করা হয় তাকে  Primary key বলে। একটি টেবিলের ID কিংবা অন্যান্য ডেটা অন্য একটি টেবিলের ব্যবহার করার জন্য যেই key ব্যবহার করা হয় তাকে Foreign key বলে।

### 4. What is the difference between the VARCHAR and CHAR data types?
varchar এবং char দুটি PostgreSQL টেক্সট ডেটা সংরক্ষণের জন্য ব্যবহার করা হয়। varchar পরিবর্তনশীল টেক্সট ধরে এবং char নির্দিষ্ট দৈর্ঘ্যের টেক্সট ধরে। ছোট ডেটার ক্ষেত্রে char একটু বেশি দ্রুত কাজ করে এবং বড় ও পরিবর্তনশিল ডেটার ক্ষেত্রে varchar খুবই গুরুত্বপূর্ণ। তবে c চেয়ে বর্তমানে varchar  বেশি ব্যবহার করা হয় ।

### 5. Explain the purpose of the WHERE clause in a SELECT statement.
WHERE clause হল SQL এর একটি গুরুত্বপূর্ণ অংশ যা SELECT statement এ নির্দিষ্ট শর্ত অনুযায়ী ডেটা ফিল্টার করে আনার জন্য ব্যবহার করা হয়। এক্ষেত্রে ডাটাবেজ থেকে শুধুমাত্র সেই ডেটা গুলো আনা হয় যেগুলো কোন একটি নির্দিষ্ট শর্ত পূরণ করে।

` SELECT * species WHERE discovery_date < '1800-01-01' `