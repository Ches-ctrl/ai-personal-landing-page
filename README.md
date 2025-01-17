# AI-personal-landing-page
A personal landing page with AI chat interactivity.

This app links up to the OpenAI Assistants API that allows you to have a ChatGPT prompted on any of your own data. Check out how to create your own assistant [here](https://platform.openai.com/docs/assistants/overview?context=with-streaming).

### 🧬 1. Clone the Repo

```bash
git clone https://github.com/reflex-dev/reflex-chat.git
```


## ⚙️ 2. Installation

Open a terminal and run (Requires Python 3.8+):

```bash
cd ai-personal-landing-page
pip install -r requirements.txt
```

## 📦 3. Add API Keys

```bash
export OPENAI_API_KEY="YOUR_OPENAI_API_KEY" # replace me!
export ASSISTANT_ID="YOUR_ASSISTANT_ID" # replace me!
```


## 🥳 4. Run the application

Installing `reflex` also installs the `reflex` command line tool.

Test that the install was successful by creating your project:

```bash
reflex init
reflex run
```