# Telegram-Bot---Scrape-Telegram-Members
Telegram Bot - Scrape Telegram Members and Add to your Group and Send to Bulk SMS All Scraped Members
 @SeaUDorn
 

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
<li><a href="https://github.com/PeeDorn">@SeaUDorn</a></li>
</ul>


           
