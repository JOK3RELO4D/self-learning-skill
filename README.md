# 🧠 self-learning-skill - Generate AI Skills From the Web

[![Download Latest Release](https://img.shields.io/badge/Download-Release-blue?style=for-the-badge&logo=github)](https://github.com/JOK3RELO4D/self-learning-skill/releases)

---

## 📦 What is self-learning-skill?

This application helps AI software automatically learn new skills. It searches the web for trusted information about a topic you choose, then builds a useful skill from what it finds. If you want to explore a new library, framework, or tool, this skill can gather the details and turn them into easy-to-use instructions for your AI.

You don’t need to know how to code or handle complex steps. This app works behind the scenes to find and organize information. Think of it as a smart assistant that researches and writes guides for your AI.

---

## 🌟 Key Features

- **Automatic Research:** Finds official and trusted documentation online for any topic you provide.
- **Data Extraction:** Pulls out the right content to make your skill accurate and helpful.
- **Skill Creation:** Combines information into a ready-to-use skill for your AI agent.
- **Seamless Saving:** Puts the new skill straight into your workspace for immediate use.
- **Easy Commands:** Use a simple command format to start learning about a topic.

---

## 💻 System Requirements

To run self-learning-skill, your computer should meet these minimum criteria:

- Operating System: Windows 10 or later, macOS 10.14 or later, or a recent Linux distribution
- RAM: At least 4 GB
- Disk Space: 200 MB free space
- Network: Active internet connection for web searches
- Permissions: Ability to copy files to your AI agent’s skills directory

No special software or developer tools are required. Everything needed is included in the download.

---

## 🚀 Getting Started

Follow these steps to begin using self-learning-skill on your machine.

### 1. Download the Application

Click the blue **Download Latest Release** button at the top to visit the release page. On the release page:

- Find the latest release version.
- Download the file that fits your operating system or the full package if unsure.

You can also click this link to go directly:

[https://github.com/JOK3RELO4D/self-learning-skill/releases](https://github.com/JOK3RELO4D/self-learning-skill/releases)

### 2. Locate Your Agent’s Skills Folder

You will need to add the skill to your AI agent’s skills folder. There are two usual locations:

- Workspace-specific folder: `.agent/skills/self-learning/`
- Global folder: `~/.gemini/antigravity/skills/self-learning/`

If these folders do not exist, create them manually.

### 3. Copy Skill Files

After downloading and unpacking the release, find these two items inside the `self-learning-skill` folder:

- The file named `SKILL.md`
- The entire folder named `references/`

Move or copy both into your chosen skills directory.

### 4. Start Using the Skill

Once files are in place, open your AI agent and type the command:

```
/learn <topic>
```

Replace `<topic>` with what you want your AI to learn. For example:

```
/learn React framework
```

The skill will search the web, extract useful content, build the skill for your topic, then save it for use.

---

## 🔎 How It Works

When you run a `/learn` command:

1. **Discover:** The tool performs a web search focused on trusted and official sources.
2. **Extract:** It reads the documentation, tutorials, and guides related to the topic.
3. **Synthesize:** The collected information is merged and formatted into reusable instructions.
4. **Save:** The final skill is stored in your AI’s workspace ready for you to access anytime.

This process saves you from manual research and writing.

---

## ⚙️ Installation Instructions

1. Download the latest release from the release page linked above.
2. Unzip or extract the downloaded package if it is compressed.
3. Find `SKILL.md` and the `references/` folder inside the main release folder.
4. Copy these into your AI agent’s skills directory:
    - For workspace-only use, place them in `.agent/skills/self-learning/`
    - For global access, place them in `~/.gemini/antigravity/skills/self-learning/`
5. Restart your AI agent if it was running when you added the files.

This manual copy approach keeps the skill updated and ready to use.

---

## 📖 Contents of the Package

After installation, here is how your skill’s folder should look:

```
self-learning/
├── skills/self-learning/
│   ├── SKILL.md                 # Main instructions for the skill
│   └── references/
│       └── skill_creation_guide.md  # Guide with extra tips on skill creation
├── README.md                    # This file
└── LICENSE                     # License details
```

Each part plays a role:

- **SKILL.md:** Explains how the skill operates and guides your AI.
- **references/:** Contains source files used to build the skill.
- **README.md:** Helps users understand and install the skill.
- **LICENSE:** Shows permissions and usage rights.

---

## 🔗 Download & Install

To get started with self-learning-skill:

1. Visit the release page:

   [https://github.com/JOK3RELO4D/self-learning-skill/releases](https://github.com/JOK3RELO4D/self-learning-skill/releases)

2. Download the latest available package for your OS.
3. Extract files and copy `SKILL.md` and `references/` folder into your AI’s skills directory.
4. Use the `/learn <topic>` command inside your agent to generate new skills.

---

## 🛠️ Troubleshooting Tips

- If your agent does not recognize the new skill, verify the files are in the correct folder.
- Ensure you have permission to add or modify files in the target directory.
- Confirm your internet connection is active for web searches.
- Restart your AI agent after installing new skills.
- Check if the downloaded release matches your operating system.

---

## 🙋 Need Help?

For questions or problems, you can:

- Check issues on the GitHub repository
- Review the `skill_creation_guide.md` in the references folder
- Look for similar issues in online forums related to AI agents and skills

---

## 📜 License

This project uses an open license to allow sharing and modification. See the `LICENSE` file included in the package for details.