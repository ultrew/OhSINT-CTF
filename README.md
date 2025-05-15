# 🕵️‍♂️ OSINT CTF Challenge – "Who is this guy?"

Welcome to this fun and beginner-friendly OSINT (Open Source Intelligence) CTF challenge! Your goal is to track down information about a target based on publicly available clues scattered across the web.

---

## 📜 Description

You've been handed a screenshot with a few key details about a person. Using OSINT techniques, your task is to answer the following questions:

- What is this user's avatar of?
- What city is this person in?
- What is the SSID of the WAP he connected to?
- What is his personal email address?
- What site did you find his email address on?
- Where has he gone on holiday?
- What is the person's password?

Sounds simple? Let’s see how well you can dig!

---

## 🧩 Challenge File

You’ll need this image to begin your investigation:

👉 [`ohshint ans.jpg`](./ohshint%20ans.jpg)

---

## 💡 Hints (Mapped to Questions)

| # | Hint                                                                 |
|---|----------------------------------------------------------------------|
| 1 | `exiftool` is your friend. Who is the author of the image? Do they have any social media accounts? |
| 2 | Use the **BSSID** and search it on [Wigle.net](https://wigle.net)   |
| 6 | If the website is not available, check it on the [Wayback Machine](https://archive.org/web/) |
| 7 | Check the **source code** of the website or page                    |

---

## 🔧 Tools You Might Need

- [ExifTool](https://exiftool.org/)
- [Wigle.net](https://wigle.net)
- [Wayback Machine](https://archive.org/web/)
- [Google Dorking](https://www.exploit-db.com/google-hacking-database)
- [GitHub](https://github.com/)
- Basic knowledge of image metadata and source code inspection

---

## ✅ Answers Preview (Spoiler Warning)

> ![Answers Image](./ohshint%20ans.jpg)

> ⚠️ **Don't use these answers until you're done solving!**  
> Try your best using the hints and tools provided before peeking. The learning is in the hunt. 🕵️‍♀️

---

## 📚 Learning Objectives

By completing this challenge, you’ll practice:

- Extracting image metadata (EXIF)
- Finding BSSID geolocation data
- Performing social media and email footprinting
- Using archived websites and GitHub profile data
- Thinking like a real-world OSINT analyst

---

## 🏁 Good Luck!

Put on your detective hat and begin the hunt!  
Found this challenge fun or have suggestions? Open an issue or submit a pull request!

