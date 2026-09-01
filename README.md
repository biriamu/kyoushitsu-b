# Welcome to the Kyoushitsu B GitHub Repository!
Kyoushitsu B is a Wiki Database for information related to mobile rhythm games. This GitHub repository serves as the underlying code for the Wiki, which is served via Cloudflare Pages.


![Tenma Saki](docs/images/Saki.webp)

## For Contributors
For those interested in contributing to this project, please join the [Discord server](https://kyoushitsu.biriamu.com/) and shoot me a message!

## To contribute directly to the project, ensure you have and/or are familiar with the following tools.
- A code editor/IDE ([VS Code](https://code.visualstudio.com/), [VSCodium](https://vscodium.com/), etc., VSCodium is the recommended open-source variant of VS Code.)
- [Python](https://www.python.org/) and pip
- [GitHub Desktop](https://desktop.github.com/download/) (optional but highly recommended)
- Markdown
- HTML

### Step 1
- Pull the repository with the URL ```https://github.com/biriamu/kyoushitsu-b``` into the GitHub Desktop application, or with your method of choice.
### Step 2
- In the terminal, change your directory directory to the repository you cloned by entering ```cd ~/path/to/kyoushitsu-b``` on MacOS/Linux, or ```cd C:\path\to\kyoushitsu-b``` on Windows.
- Install [Zensical](https://zensical.org/docs/get-started/#install-with-pip). Follow the "Install with pip" instructions for your respective operating system.
### Step 2
- In VS Code or VSCodium, open the *kyoushitsu-b* folder
- Open a new terminal environment in the editor and type ```source .venv/bin/activate``` in Linux/MacOS or ```.venv\Scripts\activate``` in Windows to enter a virtual Python environment.
- To view your changes in a live environment on the browser as you edit, open a terminal and type ```zensical serve``` in the directory of the local repository. Then navigate to ```http://localhost:8000/``` in your browser of choice.
- If an error prevents the page from displaying properly, make sure to also install the Wiki's theme by running ```pip install catppuccin-zensical``` in the terminal.
- Follow the [Zensical documentation](https://zensical.org/docs/) for more information on changes you can make to the Wiki.
### Step 4
- After you have finished your edits, create a new Pull Request in GitHub Desktop (or in your method of choice) and submit your code to a new branch.
- The code will be reviewed and merged to the main branch after approval.

For more questions, please do not hesitate to ask me in the [Discord server](https://kyoushitsu.biriamu.com/)!

Kyoushitsu B is powered by [Zensical](https://zensical.org/).
