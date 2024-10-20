# web_scraping_assignments
Project Overview

For this assignment, I selected the Lord of the Rings Fandom Wiki to scrape character data. I chose this wiki because it contains rich and well-organized information about characters in the Lord of the Rings universe, specifically for characters in the "Rings of Power" adaptation.

This data can be useful to researchers interested in exploring how fan communities catalog detailed character information. The data collected, such as character names and their respective links, could help analyze the popularity and organization of character data across different adaptations of Lord of the Rings.

Legal and Ethical Considerations

Before starting the scraping process, I reviewed the robots.txt file for the Lord of the Rings Fandom Wiki to ensure scraping is allowed. Below is the link to the robots.txt file:

https://lotr.fandom.com/robots.txt
Scraping Permissions:
Allowed: Regular wiki pages (e.g., character pages) and API endpoints (/api.php?) are allowed for scraping.
Disallowed: Special pages (e.g., /wiki/Special:, /wiki/User:, /wiki/Template:, etc.) are restricted and have not been scraped in this project.
Data Collection Process

I used the following steps to scrape data from the Lord of the Rings Fandom Wiki:

Scraping Target: Canon character names and their corresponding wiki page links from the Rings of Power section.
Libraries Used:
requests: To retrieve the HTML content of the wiki page.
BeautifulSoup: To parse and extract specific data (character names and links).
Data Output: The scraped data has been saved in a CSV file (lotr_canon_characters.csv), which includes the character name and the link to their wiki page.
