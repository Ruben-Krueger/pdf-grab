 # PDF Parsing

This is a script I wrote several years ago to parse values from PDFs generated from Flywheel. This script assumes that the relevant data files are located in `./data`. Having learned a thing or two about programming since then, if I wrote this now, I would make a number of improvements, including:
- Properly handling dependencies by using a `requirements.txt` file
- Improving robustness by better commenting the regular expressions used
- Reduce overengineering by refactoring some of the functions