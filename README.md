<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Piyush Dhadse - GitHub Profile README</title>
  <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;500;600&display=swap');
    
    body {
      font-family: 'Fira Code', monospace;
      background: linear-gradient(135deg, #0D1117 0%, #161B22 50%, #0D1117 100%);
      min-height: 100vh;
    }
    
    .glow {
      box-shadow: 0 0 20px rgba(0, 247, 255, 0.3);
    }
    
    .glow:hover {
      box-shadow: 0 0 30px rgba(0, 247, 255, 0.5);
    }
    
    textarea {
      font-family: 'Fira Code', monospace;
      font-size: 12px;
      line-height: 1.5;
    }
    
    ::-webkit-scrollbar {
      width: 8px;
      height: 8px;
    }
    
    ::-webkit-scrollbar-track {
      background: #161B22;
    }
    
    ::-webkit-scrollbar-thumb {
      background: #00F7FF;
      border-radius: 4px;
    }
    
    .copied-toast {
      animation: slideIn 0.3s ease-out;
    }
    
    @keyframes slideIn {
      from { transform: translateY(-20px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
  </style>
</head>
<body class="text-white p-4 md:p-8">
  <div class="max-w-5xl mx-auto">
    <!-- Header -->
    <div class="text-center mb-8">
      <h1 class="text-3xl md:text-4xl font-bold mb-2" style="color: #00F7FF;">
        <i class="fab fa-github mr-2"></i>GitHub Profile README
      </h1>
      <p class="text-gray-400">Enhanced profile for Piyush Dhadse</p>
    </div>
    
    <!-- Toast Notification -->
    <div id="toast" class="fixed top-4 right-4 bg-green-600 text-white px-6 py-3 rounded-lg hidden copied-toast z-50">
      <i class="fas fa-check-circle mr-2"></i>Copied to clipboard!
    </div>
    
    <!-- Copy Button -->
    <div class="flex justify-end mb-4">
      <button 
        onclick="copyToClipboard()" 
        class="glow bg-gradient-to-r from-cyan-500 to-blue-600 hover:from-cyan-400 hover:to-blue-500 text-white font-bold py-3 px-6 rounded-lg transition-all duration-300 flex items-center gap-2"
      >
        <i class="fas fa-copy"></i>
        Copy README.md
      </button>
    </div>
    
    <!-- Markdown Content -->
    <div class="glow bg-gray-900 rounded-xl border border-gray-700 overflow-hidden">
      <div class="flex items-center gap-2 px-4 py-3 bg-gray-800 border-b border-gray-700">
        <div class="w-3 h-3 rounded-full bg-red-500"></div>
        <div class="w-3 h-3 rounded-full bg-yellow-500"></div>
        <div class="w-3 h-3 rounded-full bg-green-500"></div>
        <span class="ml-2 text-gray-400 text-sm">README.md</span>
      </div>
      <textarea 
        id="markdown-content" 
        readonly 
        class="w-full h-[70vh] p-4 bg-gray-900 text-gray-300 resize-none focus:outline-none"
      ># 🚀 Enhanced GitHub Profile README

<!-- Animated Header -->
<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=4500&color=00F7FF&center=true&vCenter=true&width=750&lines=Hi+there!+I'm+Piyush+👋;System+Optimizer+%7C+Creative+Engineer;Full-Stack+Developer+%7C+Problem+Solver;Welcome+to+my+GitHub+Profile!" alt="Typing SVG" />
</div>

<!-- Profile Picture with Animation -->
<div align="center">
  <img src="https://github.com/PiyushDhadse.png" width="180" height="180" style="border-radius:50%;" alt="Piyush Dhadse" />
</div>

<br>

<!-- Elegant Animated Divider -->
<div align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" alt="divider" width="100%" />
</div>

## 🛠️ Tech Stack & Tools

<div align="center">

### **Frontend Development**
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)

### **Backend & Databases**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

### **Programming Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)

### **Tools & Platforms**
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)

</div>

<br>

## 👨‍💻 About Me

<div align="center">

```javascript
const piyush = {
  pronouns: "He" | "Him",
  code: ["JavaScript", "Python", "C++", "HTML/CSS"],
  technologies: {
    frontend: ["React", "Next.js", "Tailwind CSS"],
    backend: ["Node.js", "Express", "MongoDB"],
    hardware: ["ESP32", "Arduino", "Raspberry Pi"],
    tools: ["Git", "Docker", "VS Code", "Postman"]
  },
  focus: [
    "System Optimization",
    "Full-Stack Development",
    "Creative Engineering",
    "Prompt Engineering",
    "Digital Art Workflows"
  ],
  motto: "Build efficient solutions for complex problems"
};
```

</div>

<br>

## 📊 GitHub Analytics

<div align="center">

<table>
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=PiyushDhadse&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=00F7FF&icon_color=00F7FF&text_color=FFFFFF&include_all_commits=true&count_private=true" alt="Piyush's GitHub Stats" width="100%" />
    </td>
    <td>
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=PiyushDhadse&theme=dark&hide_border=true&background=0D1117&ring=00F7FF&fire=00F7FF&currStreakLabel=00F7FF" alt="GitHub Streak" width="100%" />
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=PiyushDhadse&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&title_color=00F7FF&text_color=FFFFFF&langs_count=8&hide=Jupyter%20Notebook" alt="Top Languages" width="100%" />
    </td>
  </tr>
</table>

</div>

<br>

## 🎯 Current Focus

<div align="center">

| Area | Details |
|:---:|:---|
| 🤖 | **Prompt Engineering** - AI Integration & Automation |
| 💼 | **SaaS Development** - Scalable Architecture |
| ⚡ | **System Optimization** - Performance Tuning |
| 🎨 | **Creative Workflows** - Digital Art Tools |

</div>

<br>

## 📫 Let's Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://piyushdhadse.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/piyush-dhadse-7269bb32b/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhadsepiyush54@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PiyushDhadse)

</div>

<br>

## 📈 Contribution Graph

<div align="center">

[![Piyush's GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=PiyushDhadse&theme=react-dark&bg_color=0D1117&color=00F7FF&line=00F7FF&point=FFFFFF&hide_border=true&area=true)](https://github.com/PiyushDhadse)

</div>

<br>

## 🏆 GitHub Trophies

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=PiyushDhadse&theme=onedark&row=2&column=3&no-bg=true&no-frame=true&margin-w=15&margin-h=15)](https://github.com/ryo-ma/github-profile-trophy)

</div>

<br>

<!-- Footer -->
<div align="center">

![Visitor Count](https://komarev.com/ghpvc/?username=PiyushDhadse&color=00F7FF&style=for-the-badge&label=PROFILE+VIEWS)

### 💡 Philosophy
> *"First, solve the problem. Then, write the code." – John Johnson*

</div>

---

<div align="center">
  
⭐ *Feel free to explore my repositories and don't hesitate to reach out for collaboration!*

**Made with ❤️ by Piyush Dhadse**

</div>
      </textarea>
    </div>
    
    <!-- Instructions -->
    <div class="mt-6 p-4 bg-gray-800 rounded-lg border border-gray-700">
      <h3 class="text-lg font-bold mb-2" style="color: #00F7FF;">
        <i class="fas fa-info-circle mr-2"></i>How to Use
      </h3>
      <ol class="list-decimal list-inside text-gray-400 space-y-2">
        <li>Click the <strong class="text-white">"Copy README.md"</strong> button above</li>
        <li>Go to your GitHub profile repository (<code class="bg-gray-700 px-2 py-1 rounded">github.com/YourUsername/YourUsername</code>)</li>
        <li>Create or edit the <code class="bg-gray-700 px-2 py-1 rounded">README.md</code> file</li>
        <li>Paste the copied content and commit changes</li>
      </ol>
    </div>
    
    <!-- Footer -->
    <div class="text-center mt-8 text-gray-500">
      <p>Made with <span class="text-red-500">❤️</span> for Piyush Dhadse</p>
    </div>
  </div>
  
  <script>
    function copyToClipboard() {
      const textarea = document.getElementById('markdown-content');
      textarea.select();
      textarea.setSelectionRange(0, 99999);
      
      navigator.clipboard.writeText(textarea.value).then(() => {
        const toast = document.getElementById('toast');
        toast.classList.remove('hidden');
        
        setTimeout(() => {
          toast.classList.add('hidden');
        }, 2000);
      });
    }
  </script>
</body>
</html>
