<h1 align="center">
  <br>
  <a href="https://github.com/5HR3D/GDorker"><img src="https://github.com/5HR3D/GDorker/blob/main/screenshot.png" alt="gdorker"></a>
  <br>
  GDorker
  </h1>
<p align="center">Just a simple Google URL scraper.</p>

# Intro
GDorker is a web scraper which scrapes Google URL's and is made purely with Python-3. It has two main scraping options:
- <a href="https://github.com/5HR3D/GDorker#query-dorking">Query dorking</a>
- <a href="https://github.com/5HR3D/GDorker#website-dorking">Website dorking</a>
- <a href="https://github.com/5HR3D/GDorker#darkweb-dorking-rudra">Onion dorking [RUDRA]</a>

## Query dorking
Scrapes URL's displayed in google for a specific search query given by the user and saves it to a file  named 'links.txt' and also prints the url in the  terminal. It also asks you how many top url's to scrape according to your requirements.

## Website dorking
Scrapes a website. After the URL of a website is given it searches for indexed links for:
- Directory lisiting vulnerabilities
- Configuration files exposed
- Database files exposed
- Log files exposed
- Backup and old files
- Login pages
- SQL errors
- Publicly exposed documents
- PHPinfo() files<br>
then register's the  results in a html file with the website's URL in its file name.

## Onion dorking [RUDRA]
Scrapes onion URLs for a given keyword.<br>Thanks to <a href="https://github.com/d4rk-vamp1re/">D4rk Vamp1re</a>.

## Usage

Clone the repository
```sh
$ git clone https://github.com/5HR3D/GDorker.git
```
Open folder
```sh
$ cd GDorker
```
Run
```sh
$ python3 dorker.py
```

## Dependencies
- <a href="https://pypi.org/project/google/">google</a> 
- <a href="https://pypi.org/project/requests/">requests</a>

## Prerequisites
- <a href="https://www.python.org/download/releases/3.0/">Python3</a>
- Python3-pip
- Python3-setuptools
- Git

### Disclaimer 
GDorker was created for educational and personal purposes only. The creators will not be held responsible for any violations of law caused by any means by anyone. Please use this tool at your own risk.

## Contact
Mail: its5hr3d@protonmail.com <br>
Or: https://linktr.ee/5HR3D

### © Copyrights 5HR3D
Thank You
