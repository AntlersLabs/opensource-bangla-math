# Bangla Math Problem Dataset

![License](https://img.shields.io/badge/license-MIT-green)

Welcome to the **Bangla Math Problem Dataset**, an open-source collection of math problems in the Bangla language. This dataset was originally in CSV format and has been converted to JSON by **Antlers Labs** for easier usability and integration into various applications.

## About the Dataset

This dataset contains a wide variety of math problems written in Bangla, covering different topics and difficulty levels. It is suitable for researchers, educators, students, or developers who are interested in building educational tools, machine learning models, or any other projects that involve Bangla language processing or math problem-solving.

### Key Features:
- **Language**: Bangla (বাংলা)
- **Format**: JSON (converted from CSV)
- **Size**: [400MB]
- **Topics Covered**: Arithmetic, Algebra, Geometry, Calculus, etc.
- **Difficulty Levels**: Beginner to Advanced

## Usage

You can use this dataset for a variety of purposes, including but not limited to:

- Training machine learning models for natural language processing (NLP) tasks.
- Building educational platforms or apps focused on math education in Bangla.
- Research in Bangla language processing and math problem-solving algorithms.
- Generating quizzes or exercises for students.

### Example JSON Structure

Each entry in the dataset follows this structure:

```json
{
  "problem": "5 জন ছাত্র 3টি খেলার প্রতিযোগিতায় অংশগ্রহণের জন্য সাইন আপ করছে, প্রত্যেকে মাত্র একটি ইভেন্টের জন্য সাইন আপ করতে পারবে।
  সাইন আপ করার বিভিন্ন উপায়ের সংখ্যা হল:\n\nA: 243\n\nB: 125\n\nC: 60\n\nD: 120",
  "solution": "এই সমস্যা সমাধান করার জন্য, আমরা গুণন নিয়ম ব্যবহার করে গণনা নীতি প্রয়োগ করি। যেহেতু 5 জন ছাত্র আছে এবং প্রতিটি ছাত্র 3টি খেলার প্রতিযোগিতার মধ্যে একটির জন্য সাইন আপ করতে পারে, তাই আমরা গণনাকে নিম্নলিখিতভাবে ভাগ করতে পারি:\n\n- প্রথম ছাত্রের 3টি খেলার প্রতিযোগিতা
  থেকে সাইন আপ করার জন্য 3টি বিকল্প আছে।\n- দ্বিতীয় ছাত্রেরও 3টি বিকল্প আছে, প্রথম ছাত্রের পছন্দের উপর নির্ভর করে না।\n- এই ধারা 5 জন ছাত্রের জন্য চলতে থাকে,
  প্রত্যেকে 3টি বিকল্প রয়েছে।\n\nঅতএব, সাইন আপ করার বিভিন্ন উপায়ের মোট সংখ্যা প্রতিটি ছাত্রের বিকল্প সংখ্যা গুণ করে গণনা করা হয়:\n\n\\[3 \\times 3 \\times 3 \\times 3 \\times 3 = 3^5\\]\n\nঘাতটি
  গণনা করি:\n\n\\[3^5 = 243\\]\n\nঅতএব, খেলার প্রতিযোগিতার জন্য সাইন আপ করার বিভিন্ন উপায়ের সংখ্যা হল $\\boxed{243}$।  এটি A বিকল্পের সাথে মিলে যায়।"
}
