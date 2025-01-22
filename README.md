# Telegram-Bot---Scrape-Telegram-Members
Telegram Bot - Scrape Telegram Members and Add to your Group and Send to Bulk SMS All Scraped Members
 @SeaUDorn
 
[Environment Setup:]
Download and Install Python:

[Visit] python.org/downloads to download and install Python for your operating system.
Set up the Python environment path in Windows, Linux, or macOS.
Download and Install VS Code:

Visit code.visualstudio.com/download to download and install VS Code for your operating system.
Create Python Virtual Environment:

Open your terminal in the project directory or Open the project directory in VS code.
Run the command: python -m venv env to create a virtual environment.
Activate the environment :

Windows: .\env\Scripts\activate
Linux or macOS: source env/bin/activate
Install Project Dependencies:

Run: pip install -r requirements.txt to install project dependencies.
Create Telegram API Token:

Go to my.telegram.org/auth.
Enter your phone number and set up the API information to generate an API token.
Documentation:
Step 1: Setup Accounts

Open the terminal in the project directory.
Run python authenticate.py.
Choose option 1 to enter new accounts.
Enter Api id, Api hash, and phone number.
If adding more accounts, enter 'y'; if not, enter 'n'.
Choose option 2 to filter all banned accounts.
Choose option 3 to show all accounts.
Choose option 4 to delete accounts.
Step 2: Scraping Members

Run python member_scraper.py in the terminal.
Choose an account to scrape.
Choose to scrape from a public or private group.
PUBLIC GROUPS: Suppose public group username is @PythonHub. Enter only 'PythonHub'. Omit '@' and hit enter
PRIVATE GROUPS: Copy invite link and paste in the terminal and hit enter.
Choose whether to filter active users.
Step 3: Adding Members

Launch python member_adder.py in the terminal.
It'll create sessions and prompt for a login code if not logged in.
Enter the username of the public group without '@'.
Enter the number of accounts to use.
Read the warning and press enter to proceed.
It'll add members using the specified accounts.
Troubleshooting:

Members Not Getting Added:

It may be due to account limitations. Try using other accounts.
Error While Logging In:

If you have two-factor authentication enabled, turn it off. You can turn it back on after logging in.
For any problems, open an issue on GitHub or contact the developer via the Telegram group mentioned in the README.md.

Step 4: Send Bulk Messages

Launch python bulk_sms.py in the terminal.
Select the number and enter.
Choose the option to send a message based on the member's username or user ID.
It will send the message to all members in the group.
Ensure to follow the documentation properly for smooth execution of the project.
Authors
@SeaUDorn
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">Environment Setup:</h2><a id="user-content-environment-setup" class="anchor" aria-label="Permalink: Environment Setup:" href="#environment-setup"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li>
<p dir="auto"><strong>Download and Install Python:</strong></p>
<ul dir="auto">
<li>Visit <a href="https://www.python.org/downloads/" rel="nofollow">python.org/downloads</a> to download and install Python for your operating system.</li>
<li>Set up the Python environment path in Windows, Linux, or macOS.</li>
</ul>
<p dir="auto"><strong>Download and Install VS Code:</strong></p>
<ul dir="auto">
<li>Visit <a href="https://code.visualstudio.com/download" rel="nofollow">code.visualstudio.com/download</a> to download and install VS Code for your operating system.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>Create Python Virtual Environment:</strong></p>
<ul dir="auto">
<li>Open your terminal in the project directory or Open the project directory in VS code.</li>
<li>Run the command: <code>python -m venv env</code> to create a virtual environment.</li>
</ul>
<p dir="auto"><strong>Activate the environment :</strong></p>
<ul dir="auto">
<li>Windows: <code>.\env\Scripts\activate</code></li>
<li>Linux or macOS: <code>source env/bin/activate</code></li>
</ul>
</li>
<li>
<p dir="auto"><strong>Install Project Dependencies:</strong></p>
<ul dir="auto">
<li>Run: <code>pip install -r requirements.txt</code> to install project dependencies.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>Create Telegram API Token:</strong></p>
<ul dir="auto">
<li>Go to <a href="https://my.telegram.org/auth" rel="nofollow">my.telegram.org/auth</a>.</li>
<li>Enter your phone number and set up the API information to generate an API token.</li>
</ul>
</li>
</ol>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">Documentation:</h2><a id="user-content-documentation" class="anchor" aria-label="Permalink: Documentation:" href="#documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong>Step 1: Setup Accounts</strong></p>
<ul dir="auto">
<li>Open the terminal in the project directory.</li>
<li>Run <code>python authenticate.py</code>.
<ul dir="auto">
<li>Choose option 1 to enter new accounts.</li>
<li>Enter Api id, Api hash, and phone number.</li>
<li>If adding more accounts, enter 'y'; if not, enter 'n'.</li>
<li>Choose option 2 to filter all banned accounts.</li>
<li>Choose option 3 to show all accounts.</li>
<li>Choose option 4 to delete accounts.</li>
</ul>
</li>
</ul>
<p dir="auto"><strong>Step 2: Scraping Members</strong></p>
<ul dir="auto">
<li>Run <code>python member_scraper.py</code> in the terminal.
<ul dir="auto">
<li>Choose an account to scrape.</li>
<li>Choose to scrape from a public or private group.
<ul dir="auto">
<li>PUBLIC GROUPS: Suppose public group username is @PythonHub. Enter only 'PythonHub'. Omit '@' and hit enter</li>
<li>PRIVATE GROUPS: Copy invite link and paste in the terminal and hit enter.</li>
</ul>
</li>
<li>Choose whether to filter active users.</li>
</ul>
</li>
</ul>
<p dir="auto"><strong>Step 3: Adding Members</strong></p>
<ul dir="auto">
<li>Launch <code>python member_adder.py</code> in the terminal.</li>
<li>It'll create sessions and prompt for a login code if not logged in.</li>
<li>Enter the username of the public group without '@'.</li>
<li>Enter the number of accounts to use.</li>
<li>Read the warning and press enter to proceed.</li>
<li>It'll add members using the specified accounts.</li>
</ul>
<p dir="auto"><strong>Troubleshooting:</strong></p>
<ol dir="auto">
<li>
<p dir="auto"><strong>Members Not Getting Added:</strong></p>
<ul dir="auto">
<li>It may be due to account limitations. Try using other accounts.</li>
</ul>
</li>
<li>
<p dir="auto"><strong>Error While Logging In:</strong></p>
<ul dir="auto">
<li>If you have two-factor authentication enabled, turn it off. You can turn it back on after logging in.</li>
</ul>
</li>
</ol>
<p dir="auto">For any problems, open an issue on GitHub or contact the developer via the Telegram group mentioned in the README.md.</p>
<p dir="auto"><strong>Step 4: Send Bulk Messages</strong></p>
<ul dir="auto">
<li>Launch <code>python bulk_sms.py</code> in the terminal.</li>
<li>Select the number and enter.</li>
<li>Choose the option to send a message based on the member's username or user ID.</li>
<li>It will send the message to all members in the group.</li>
</ul>
<p dir="auto">Ensure to follow the documentation properly for smooth execution of the project.</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">Color Reference</h2><a id="user-content-color-reference" class="anchor" aria-label="Permalink: Color Reference" href="#color-reference"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th>Color</th>
<th>Hex</th>
</tr>
</thead>
<tbody>
<tr>
<td>Example Color</td>
<td><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/fdb37522fe51f04bff7a438e195d5d2b308a01991997eb8e75091632990398f0/68747470733a2f2f7669612e706c616365686f6c6465722e636f6d2f31302f3061313932663f746578743d2b"><img src="https://camo.githubusercontent.com/fdb37522fe51f04bff7a438e195d5d2b308a01991997eb8e75091632990398f0/68747470733a2f2f7669612e706c616365686f6c6465722e636f6d2f31302f3061313932663f746578743d2b" alt="#0a192f" data-canonical-src="https://via.placeholder.com/10/0a192f?text=+" style="max-width: 100%;"></a> #0a192f</td>
</tr>
<tr>
<td>Example Color</td>
<td><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/311954feb48bb10bf303657c544597a06e5a0207161089960b0afdf8b446f210/68747470733a2f2f7669612e706c616365686f6c6465722e636f6d2f31302f6638663866383f746578743d2b"><img src="https://camo.githubusercontent.com/311954feb48bb10bf303657c544597a06e5a0207161089960b0afdf8b446f210/68747470733a2f2f7669612e706c616365686f6c6465722e636f6d2f31302f6638663866383f746578743d2b" alt="#f8f8f8" data-canonical-src="https://via.placeholder.com/10/f8f8f8?text=+" style="max-width: 100%;"></a> #f8f8f8</td>
</tr>
<tr>
<td>Example Color</td>
<td><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/3210e1102716f42c59ddfe0a26fa20975403a62ea2d41d8ca5e29aada22752ba/68747470733a2f2f7669612e706c616365686f6c6465722e636f6d2f31302f3030623438613f746578743d2b"><img src="https://camo.githubusercontent.com/3210e1102716f42c59ddfe0a26fa20975403a62ea2d41d8ca5e29aada22752ba/68747470733a2f2f7669612e706c616365686f6c6465722e636f6d2f31302f3030623438613f746578743d2b" alt="#00b48a" data-canonical-src="https://via.placeholder.com/10/00b48a?text=+" style="max-width: 100%;"></a> #00b48a</td>
</tr>
<tr>
<td>Example Color</td>
<td><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/3210e1102716f42c59ddfe0a26fa20975403a62ea2d41d8ca5e29aada22752ba/68747470733a2f2f7669612e706c616365686f6c6465722e636f6d2f31302f3030623438613f746578743d2b"><img src="https://camo.githubusercontent.com/3210e1102716f42c59ddfe0a26fa20975403a62ea2d41d8ca5e29aada22752ba/68747470733a2f2f7669612e706c616365686f6c6465722e636f6d2f31302f3030623438613f746578743d2b" alt="#00d1a0" data-canonical-src="https://via.placeholder.com/10/00b48a?text=+" style="max-width: 100%;"></a> #00d1a0</td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">Authors</h2><a id="user-content-authors" class="anchor" aria-label="Permalink: Authors" href="#authors"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://www.github.com/shamimkhaled">@shamimkhaled</a></li>
</ul>
</article></div></div></div></div></div> <!-- --> <!-- --> <script type="application/json" id="__PRIMER_DATA_:R0:__">{"resolvedServerColorMode":"day"}</script></div>
</react-partial>

      <input type="hidden" data-csrf="true" value="SRUsUrvsqVqbqpTokaCzo9Sa3TZKILcDk/H0l9sqFBYO5RKCr57IPz1qS9x9KkVFHNHfw94rCiTaEKuqyQdEvA==" />
</div>
  <div data-view-component="true" class="Layout-sidebar">      

      <div class="BorderGrid about-margin" data-pjax>
        <div class="BorderGrid-row">
          <div class="BorderGrid-cell">
            <div class="hide-sm hide-md">
  <h2 class="mb-3 h4">About</h2>

      <div class="f4 my-3 color-fg-muted text-italic">
        No description, website, or topics provided.
      </div>


    <h3 class="sr-only">Resources</h3>
    <div class="mt-2">
      <a class="Link--muted" data-analytics-event="{&quot;category&quot;:&quot;Repository Overview&quot;,&quot;action&quot;:&quot;click&quot;,&quot;label&quot;:&quot;location:sidebar;file:readme&quot;}" href="#readme-ov-file">
        <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-book mr-2">
    <path d="M0 1.75A.75.75 0 0 1 .75 1h4.253c1.227 0 2.317.59 3 1.501A3.743 3.743 0 0 1 11.006 1h4.245a.75.75 0 0 1 .75.75v10.5a.75.75 0 0 1-.75.75h-4.507a2.25 2.25 0 0 0-1.591.659l-.622.621a.75.75 0 0 1-1.06 0l-.622-.621A2.25 2.25 0 0 0 5.258 13H.75a.75.75 0 0 1-.75-.75Zm7.251 10.324.004-5.073-.002-2.253A2.25 2.25 0 0 0 5.003 2.5H1.5v9h3.757a3.75 3.75 0 0 1 1.994.574ZM8.755 4.75l-.004 7.322a3.752 3.752 0 0 1 1.992-.572H14.5v-9h-3.495a2.25 2.25 0 0 0-2.25 2.25Z"></path>
</svg>
        Readme
</a>    </div>

  



  <include-fragment  src="/shamimkhaled/telegram-scraping-adding-and-bulk-sms-bot/hovercards/citation/sidebar_partial?tree_name=main">
  </include-fragment>

  <div class="mt-2">
    <a href="/shamimkhaled/telegram-scraping-adding-and-bulk-sms-bot/activity" data-view-component="true" class="Link Link--muted"><svg text="gray" aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-pulse mr-2">
    <path d="M6 2c.306 0 .582.187.696.471L10 10.731l1.304-3.26A.751.751 0 0 1 12 7h3.25a.75.75 0 0 1 0 1.5h-2.742l-1.812 4.528a.751.751 0 0 1-1.392 0L6 4.77 4.696 8.03A.75.75 0 0 1 4 8.5H.75a.75.75 0 0 1 0-1.5h2.742l1.812-4.529A.751.751 0 0 1 6 2Z"></path>
</svg>
      <span class="color-fg-muted">Activity</span></a>  </div>


  <h3 class="sr-only">Stars</h3>
  <div class="mt-2">
    <a href="/shamimkhaled/telegram-scraping-adding-and-bulk-sms-bot/stargazers" data-view-component="true" class="Link Link--muted"><svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-star mr-2">
    <path d="M8 .25a.75.75 0 0 1 .673.418l1.882 3.815 4.21.612a.75.75 0 0 1 .416 1.279l-3.046 2.97.719 4.192a.751.751 0 0 1-1.088.791L8 12.347l-3.766 1.98a.75.75 0 0 1-1.088-.79l.72-4.194L.818 6.374a.75.75 0 0 1 .416-1.28l4.21-.611L7.327.668A.75.75 0 0 1 8 .25Zm0 2.445L6.615 5.5a.75.75 0 0 1-.564.41l-3.097.45 2.24 2.184a.75.75 0 0 1 .216.664l-.528 3.084 2.769-1.456a.75.75 0 0 1 .698 0l2.77 1.456-.53-3.084a.75.75 0 0 1 .216-.664l2.24-2.183-3.096-.45a.75.75 0 0 1-.564-.41L8 2.694Z"></path>
</svg>
      <strong>4</strong>
      stars</a>  </div>

  <h3 class="sr-only">Watchers</h3>
  <div class="mt-2">
    <a href="/shamimkhaled/telegram-scraping-adding-and-bulk-sms-bot/watchers" data-view-component="true" class="Link Link--muted"><svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-eye mr-2">
    <path d="M8 2c1.981 0 3.671.992 4.933 2.078 1.27 1.091 2.187 2.345 2.637 3.023a1.62 1.62 0 0 1 0 1.798c-.45.678-1.367 1.932-2.637 3.023C11.67 13.008 9.981 14 8 14c-1.981 0-3.671-.992-4.933-2.078C1.797 10.83.88 9.576.43 8.898a1.62 1.62 0 0 1 0-1.798c.45-.677 1.367-1.931 2.637-3.022C4.33 2.992 6.019 2 8 2ZM1.679 7.932a.12.12 0 0 0 0 .136c.411.622 1.241 1.75 2.366 2.717C5.176 11.758 6.527 12.5 8 12.5c1.473 0 2.825-.742 3.955-1.715 1.124-.967 1.954-2.096 2.366-2.717a.12.12 0 0 0 0-.136c-.412-.621-1.242-1.75-2.366-2.717C10.824 4.242 9.473 3.5 8 3.5c-1.473 0-2.825.742-3.955 1.715-1.124.967-1.954 2.096-2.366 2.717ZM8 10a2 2 0 1 1-.001-3.999A2 2 0 0 1 8 10Z"></path>
</svg>
      <strong>2</strong>
      watching</a>  </div>

  <h3 class="sr-only">Forks</h3>
  <div class="mt-2">
    <a href="/shamimkhaled/telegram-scraping-adding-and-bulk-sms-bot/forks" data-view-component="true" class="Link Link--muted"><svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-repo-forked mr-2">
    <path d="M5 5.372v.878c0 .414.336.75.75.75h4.5a.75.75 0 0 0 .75-.75v-.878a2.25 2.25 0 1 1 1.5 0v.878a2.25 2.25 0 0 1-2.25 2.25h-1.5v2.128a2.251 2.251 0 1 1-1.5 0V8.5h-1.5A2.25 2.25 0 0 1 3.5 6.25v-.878a2.25 2.25 0 1 1 1.5 0ZM5 3.25a.75.75 0 1 0-1.5 0 .75.75 0 0 0 1.5 0Zm6.75.75a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5Zm-3 8.75a.75.75 0 1 0-1.5 0 .75.75 0 0 0 1.5 0Z"></path>
</svg>
      <strong>4</strong>
      forks</a>  </div>

    <div class="mt-2">
      <a class="Link--muted" href="/contact/report-content?content_url=https%3A%2F%2Fgithub.com%2Fshamimkhaled%2Ftelegram-scraping-adding-and-bulk-sms-bot&amp;report=shamimkhaled+%28user%29">
          Report repository
</a>    </div>
</div>

          </div>
        </div>

        
            <div class="BorderGrid-row">
              <div class="BorderGrid-cell">
                <h2 class="h4 mb-3" data-pjax="#repo-content-pjax-container" data-turbo-frame="repo-content-turbo-frame">
  <a href="/shamimkhaled/telegram-scraping-adding-and-bulk-sms-bot/releases" data-view-component="true" class="Link--primary no-underline Link">Releases</a></h2>

    <div class="text-small color-fg-muted">No releases published</div>

              </div>
            </div>

        
        
            <div class="BorderGrid-row">
              <div class="BorderGrid-cell">
                
  <h2 class="h4 mb-3">
  <a href="/users/shamimkhaled/packages?repo_name=telegram-scraping-adding-and-bulk-sms-bot" data-view-component="true" class="Link--primary no-underline Link d-flex flex-items-center">Packages
      <span title="0" hidden="hidden" data-view-component="true" class="Counter ml-1">0</span></a></h2>


      <div class="text-small color-fg-muted" >
        No packages published <br>
      </div>



              </div>
            </div>

        
            <div class="BorderGrid-row" hidden>
              <div class="BorderGrid-cell">
                <include-fragment src="/shamimkhaled/telegram-scraping-adding-and-bulk-sms-bot/used_by_list" accept="text/fragment+html">
</include-fragment>
              </div>
            </div>

        
        
        
            <div class="BorderGrid-row">
              <div class="BorderGrid-cell">
                <h2 class="h4 mb-3">Languages</h2>
<div class="mb-2">
  <span data-view-component="true" class="Progress">
    <span style="background-color:#3572A5 !important;;width: 100.0%;" itemprop="keywords" data-view-component="true" class="Progress-item color-bg-success-emphasis"></span>
</span></div>
<ul class="list-style-none">
    <li class="d-inline">
        <a class="d-inline-flex flex-items-center flex-nowrap Link--secondary no-underline text-small mr-3" href="/shamimkhaled/telegram-scraping-adding-and-bulk-sms-bot/search?l=python"  data-ga-click="Repository, language stats search click, location:repo overview">
          <svg style="color:#3572A5;" aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-dot-fill mr-2">
    <path d="M8 4a4 4 0 1 1 0 8 4 4 0 0 1 0-8Z"></path>
</svg>
          <span class="color-fg-default text-bold mr-1">Python</span>
          <span>100.0%</span>
        </a>
    </li>
</ul>

              </div>
