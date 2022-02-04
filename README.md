# data4wildlife Hackathon 🛠️
**Hackathon (29-30 Jan 2022) based on developing a digital solution to prevent illegal wildlife trade(IWT) on online social platforms.**

* **Team** - Sean P. Rogers, Gabriela Youngken  👩‍🎓 👨‍🎓
* **Mentor** - Alastair Jamieson 👨‍🏫
* **Challenge** - to build a **benchmark dataset** of possible instances of different types of wildlife trafficking-related information from online social platforms which could also be searched and analyzed 🔚 
* According to the guidelines - 
    * _A benchmark dataset is a public dataset which is designed and collected for studying real-world data science/research problems._ 
    * _The benchmark dataset should be social media platform agnostic, as wildlife is trafficking across multiple platforms such as Instagram and YouTube._

## Our Task 
* **Collect instagram posts with images related to Slow Loris hashtags (slowloris, slowlorisforsale) in English, Japanese 🗾 and Thai 🇹🇭, since these were the popular locations based on our manual search** 🏛️

* **Time for the Task** - 26 hours 🏃⏲️

## Our Approach 🏗️
* Manually identify _slow loris_ hashtags 🐵
* Call the instagram api for hashtag related feed (RapidAPI, instagram85)
* Collect data and extract images
* Label images by user id
* Save images in folder labelled by language
* Iterate calls for a list of hashtags
* Collect images for human validation/future development of project into Image Recognition using deep learning algorithm (_based on size of data collected_)

 ## Major Takeaways
 * _Focus on the bigger picture_ 🌄
 * _Build one-block-at-a-time_ 🧱
 * _Have consistent breaks_ 😌

