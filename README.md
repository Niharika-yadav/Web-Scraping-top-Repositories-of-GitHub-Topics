# Web-Scraping-top-Repositories-of-GitHub-Topics

In this project, the goal was to scrape and analyze data related to various topics on GitHub, focusing on identifying and extracting information about the top repositories for each topic. The project was executed with the following key objectives:

**Scraping GitHub Topics:**
The first step involved scraping a list of topics from GitHub, where for each topic, the title, topic page URL, and topic description were extracted.

**Extracting Top Repositories:**
For each topic identified, the top 25 repositories were extracted based on their prominence on the topic page. The data retrieved for each repository included:

- **Repository Name**
- **Username of the repository owner**
- **Number of Stars indicating the repository's popularity**
- **Repository URL**

**Data Organization:**
The extracted data for each topic was organized into a CSV file, with the following columns:

- **Repo Name**
- **User Name**
- **Stars**
- **Repo URL**

**Libraries Used:**
The project made use of multiple Python libraries to facilitate web scraping, data handling, and file creation.

**Outcome:**
The result of the project is a set of CSV files, each corresponding to a specific GitHub topic, containing detailed information about the top 25 repositories associated with that topic. These files provide a structured and accessible way to analyze and utilize GitHub repository data.

# Scraping site
we're going to scrape this site:

https://github.com/topics

# Dependencies
List the dependencies required to run the project.

- **Python 3.8+**
- **Requests**
- **BeautifulSoup4**
- **Pandas**
- **Any other libraries**

# License
"This project is licensed under the MIT License - see the [LICENSE](https://github.com/Niharika-yadav/Web-Scraping-top-Repositories-of-GitHub-Topics/blob/efe444931f30ee3acefce4802c1a9451b074053c/LICENSE)
 file for details."

