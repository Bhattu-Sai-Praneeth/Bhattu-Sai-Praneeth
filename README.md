String[][] strs = new String[3][2];  // <-- Corrected size
PFont font;

void setup() {
  size(1920, 1080);
  font = createFont("HelveticaNeue-48.vlw", 48);
  textFont(font);
  frameRate(30);
  textAlign(CENTER);
  textSize(40);
  background(0);  // Dark background
  fill(255);      // White text

  strs[0][0] = "Hey there!";
  strs[0][1] = "My name is Sai Praneeth.";

  strs[1][0] = "I'm a Computer Science Major";
  strs[1][1] = "From CMR Engineering College, Hyderabad.";

  strs[2][0] = "Feel free to reach out to say hi!";
  strs[2][1] = "email: saipraneeth.bhattu@gmail.com";
}

int i = 0;
boolean delete = false;
int s = 0;
int offset = 50;
int mainFontSize = 60;
int secondaryFontSize = 40;

void draw() {
  background(0);
  fill(255);

  if (s < strs.length) {
    if ((strs[s][0].length() >= i || strs[s][1].length() >= i) && !delete) {
      if (strs[s][0].length() >= i) {
        textSize(mainFontSize);
        text(strs[s][0].substring(0, i), width/2, height/2 - offset);
      } else {
        textSize(mainFontSize);
        text(strs[s][0], width/2, height/2 - offset);
      }
      if (strs[s][1].length() >= i) {
        textSize(secondaryFontSize);
        text(strs[s][1].substring(0, i), width/2, height/2 + offset);
      } else {
        textSize(secondaryFontSize);
        text(strs[s][1], width/2, height/2 + offset);
      }
      i++;
    } else {
      if (!delete) {
        delay(1500);
      }
      delete = true;
    }

    if (delete) {
      if (i > 0) {
        if (i < strs[s][0].length()) {
          textSize(mainFontSize);
          text(strs[s][0].substring(0, i - 1), width/2, height/2 - offset);
        } else {
          textSize(mainFontSize);
          text(strs[s][0], width/2, height/2 - offset);
        }
        if (i < strs[s][1].length()) {
          textSize(secondaryFontSize);
          text(strs[s][1].substring(0, i - 1), width/2, height/2 + offset);
        } else {
          textSize(secondaryFontSize);
          text(strs[s][1], width/2, height/2 + offset);
        }
        i--;
      } else {
        delete = false;
        s++;
      }
    }
  }
}


[![](https://img.shields.io/badge/-@saipraneeth-%231DA1F2?style=flat-square&logo=twitter&logoColor=ffffff)](https://x.com/SAIPRANEETH252)
[![](https://img.shields.io/badge/-@bhattusaipraneeth-%23181717?style=flat-square&logo=github&logoColor=ffffff)](https://github.com/Bhattu-Sai-Praneeth)
[![](https://img.shields.io/badge/-Sai%20Praneeth%20Bhattu-%230077B5?style=flat-square&logo=linkedin&logoColor=ffffff)](https://www.linkedin.com/in/saipraneethbhattu/)
[![](https://img.shields.io/badge/-sai_pranee_th_b-%23E4405F?style=flat-square&logo=instagram&logoColor=ffffff)](https://www.instagram.com/sai_pranee_th_b/)
[![](https://img.shields.io/badge/-Portfolio.sai-%230ab9e6?style=flat-square&logo=google-chrome&logoColor=ffffff)](https://bhattu-sai-praneeth.github.io/Portfolio/)


## 𝗠𝘆 𝗧𝗲𝗰𝗸 𝗦𝘁𝗮𝗰𝗸

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=ffffff)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=ffffff)
![JavaScript](https://img.shields.io/badge/-JavaScript-%23F7DF1C?style=flat-square&logo=javascript&logoColor=000000&labelColor=%23F7DF1C&color=%23FFCE5A)
![HTML5](https://img.shields.io/badge/-HTML5-%23E44D27?style=flat-square&logo=html5&logoColor=ffffff)
![CSS3](https://img.shields.io/badge/-CSS3-%231572B6?style=flat-square&logo=css3)
![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat-square&logo=php&logoColor=ffffff)
![React](https://img.shields.io/badge/-React-%23282C34?style=flat-square&logo=react)
![TailwindCSS](https://img.shields.io/badge/-TailwindCSS-%231a202c?style=flat-square&logo=tailwind-css)
![Bootstrap](https://img.shields.io/badge/-Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=ffffff)
![VS Code](https://img.shields.io/badge/-VSCode-%23007ACC?style=flat-square&logo=visual-studio-code)
![PyCharm](https://img.shields.io/badge/-PyCharm-000000?style=flat-square&logo=pycharm)
![Jupyter Notebook](https://img.shields.io/badge/-Jupyter-%23F37626?style=flat-square&logo=jupyter&logoColor=ffffff)
![Google Colab](https://img.shields.io/badge/-Google%20Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=000000)
![IntelliJ IDEA](https://img.shields.io/badge/-IntelliJIDEA-000000?style=flat-square&logo=intellijidea)
![Git](https://img.shields.io/badge/-Git-%23F05032?style=flat-square&logo=git&logoColor=ffffff)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=ffffff)
![MS Office](https://img.shields.io/badge/-MS%20Office-D83B01?style=flat-square&logo=microsoft-office&logoColor=ffffff)
![AWS EC2](https://img.shields.io/badge/-AWS%20EC2-FF9900?style=flat-square&logo=amazon-aws&logoColor=000000)
![ChatGPT](https://img.shields.io/badge/-ChatGPT-412991?style=flat-square&logo=openai&logoColor=ffffff)
![Testing](https://img.shields.io/badge/-Testing-6DB33F?style=flat-square&logo=testing-library&logoColor=ffffff)
![Teamwork](https://img.shields.io/badge/-Teamwork-2E8B57?style=flat-square)
![Problem Solving](https://img.shields.io/badge/-Problem%20Solving-4682B4?style=flat-square)
![Adaptability](https://img.shields.io/badge/-Adaptability-FF8C00?style=flat-square)
![Quick Learner](https://img.shields.io/badge/-Quick%20Learner-8A2BE2?style=flat-square)
![Time Management](https://img.shields.io/badge/-Time%20Management-20B2AA?style=flat-square)


## 𝗦𝘁𝗮𝘁𝘀

![Bhattu-Sai-Praneeth's Streak](https://github-readme-streak-stats.herokuapp.com/?user=Bhattu-Sai-Praneeth&theme=highcontrast&hide_border=true)

![Bhattu-Sai-Praneeth's Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Bhattu-Sai-Praneeth&theme=highcontrast&show_icons=true&hide_border=true&layout=compact)
