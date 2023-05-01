# Installation Guidelines :rocket:

Before you start following the guidelines, make sure to go through the prerequisites section to install the required tools and packages on your machine.

**Note:** If you are a Windows user, use GitBash or PowerShell instead of the command prompt.

## Prerequisites 
1. Open AI API Keys
    - You need a paid version of the Open AI to use API keys.
2. Account in Minds DB
3. Node JS
4. Python 3.6

## Steps
1. Clone this repository and move to `kanye-ai-bot` directory
   ```sh
   git clone https://github.com/gautam071/kanye-ai-bot.git
   cd kanye-ai-bot
   ```

2. Install dependencies
   ```sh
   npm install
   ```

3. npm build
   ```sh
   npm run dev
   ```

4. Reqiurments
    ```sh
    pip3 install openai
    npm install axios
    pip3 install -r requirement.txt
    ```

5. Replace the keys
    - Search for `openai.api_key` and assign your key (File: `GPT_example_1.py`)
    - Search for `mindsdb` and assign your account username and password (File: `server.py`)

6. Server 
   ```sh 
   python3 server.py
   ```
