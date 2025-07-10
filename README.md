# emailGenarator-By-darkboss1
**DISCLAIMER**: This tool is for research purposes only.
Use this tool responsibly and ethically! I am not reliable for any abuse or harm, you may cause using it.

It is highly advisable to run the script using a VPN to enhance your privacy protection! It will also ensure your IP will not get banned due to continuous requests to the sites used (although this has never happened in any of my tests).

## Installation
To install this project run: 

```bash
# clone the repo
$ git clone https://github.com/darkboss1/emailGenarator-By-darkboss1.git

# change the working directory to emailGuesser
$ cd emailGenarator-By-darkboss1

# install requirements
python3 -m pip install -r requirements.txt

# run the script
$ python3 emailGenarator-By-darkboss1.py
```

## Usage
The script will search for potential e-mail addresses of a target according to inputs given by the user. It will try "guessing" potential e-mail addresses of the target by using the most common formats used in e-mail addresses (e.g. darkboss1@domain or j.darkboss1@domain).

The script asks for the following user inputs (mandatory inputs are marked with asterisk):
```
Name*: Insert the first name of your target (e.g. john)

Surname*: Insert the last name of your target (e.g. smith)

Birth year: Insert birth year in its full form (e.g. 1984), otherwise (e.g. if you input 84) the script will assume you don't know the exact birth year. 
You can also input "no" if you don't know the year of birth.

Username: Insert any known username of the target (only one). You can also input "no" if you don't know any username.

Add extra e-mail formats: Use static or dynamic formats for the username of the e-mail (part of e-mail before the @ symbol).
This option will add e-mail usernames to an already pre-configured list in the script (see link below for pre-configured usernames table)
If you want to add static formats just input them (e.g. josmi94) but if you want to use dynamic formats then use any structure 
containing the following: 
- f!! (first char of the target's first name), 
- first!! (target's first name), 
- l!! (first char of the target's last name) and 
- last!! (target's last name).
Example: f!!+last!! --> j+darkboss1@domain

## Contributing
If you would like to contribute to this project, you are welcome to do so. Each and every contribution is greatly valued! Keep in mind that this tool must remain
free to use for everyone, so don't use paid APIs (like Dehashed) but try finding a work around.

Right now I am working on the following TODO list:
- [ ] Find more or alternative sites to search-query that yield immediate results about the identity of the owner of an e-mail address, such as name/username etc (like Skype does)
- [ ] Find more or alternative sites/tools to search-query in order to validate e-mail addresses (not breached data)
- [ ] Find a way to query haveIbeenPwned (or similar) site faster without having to wait for 5-8 random time duration and not getting IP banned (public proxies?)
- [ ] Add more username formats that people use often before the @ symbol on e-mails and add them to the tool
- [ ] Allow users to parse a preconfigured .txt file with email formats or/and domains, so that they can automatically input the same preferences every time they run a search, without having to manually input the same things each time
- [X] Output a results.txt and a results.csv file with useful formats for an OSINT investigator
- [X] Automatically add to the search pool of potential e-mail addresses all usernames used by persons using the full name (input by user) in Skype, if user wants to.
- [ ] Remove preconfigured e-mail formats that are actually not often used by people in their e-mail addresses, to reduce execution time
- [ ] Reduce execution time by any means necessary (Right now it has an average run time of 8-10 seconds/e-mail address searched)
- [ ] Add new functions and a menu with different choices
- [ ] Add exclusive check for e-mail addresses of protonmail
- [X] Fix skypli.com 500 status error adding epieos tools as alternative skype search tool

## Feedback and Questions
For any feedback or questions please contact me on https://serialkey.top/ or serialkey.top@gmail.com

## License
MIT © 2025 emailGenarator-By-darkboss1 <br/>
Created by [White Hat Hacker](https://serialkey.top)


    ____     ___     ____     __ __    ____    ____    _____   _____   ___
   / __ \   /   |   / __ \   / //_/   / __ )  / __ \  / ___/  / ___/  <  /
  / / / /  / /| |  / /_/ /  / ,<     / __  | / / / /  \__ \   \__ \   / / 
 / /_/ /  / ___ | / _, _/  / /| |   / /_/ / / /_/ /  ___/ /  ___/ /  / /  
/_____/  /_/  |_|/_/ |_|  /_/ |_|  /_____/  \____/  /____/  /____/  /_/   
