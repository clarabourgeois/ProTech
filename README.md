# ProTech #
This project is a web application that utilizes SCSS for styling and Python for server-side logic.
It aims to create a website for an self-employed client. 

## Prerequisites #
Before building and running the project, ensure that the following tools are installed:

Ruby (to enable SCSS compilation with sass), Python 3 and pip3 (for server-side development).

## Clone the project #
To clone this project and be able to use it on your computer, you need to run the followings command : 
```
git clone https://github.com/clarabourgeois/ProTech.git
```

## Getting the webpage running #

- You need to run a small web server, use the script `./run_server.py` in the directory Site. It uses 
  python 3, make sure you have python 3 installed on you machine.
- Run the `./compile_css.sh` script to transform the SCSS source into CSS
- Access your webpage with the URLs http://localhost:8000/pages/about.html

  ## Project Structure #
```bash  
  ProTech/  
├── .idea/  
├── outils/  
├── Site/  
│   ├── .sass-cache/  
│   ├── pages/  
│   │   ├── images/                   # Folder for images  
│   │   └── outputs/                  # Folder for CSS output  
│   │       └── outputs.css           # Compiled CSS file  
│   ├── about.html                    # "About" HTML page  
│   ├── contact.html                  # "Contact" HTML page  
│   ├── domaines.html                 # "Domains" HTML page  
│   ├── nutrition.html                # "Nutrition" HTML page  
│   ├── services.html                 # "Services" HTML page  
│   └── style.scss                    # SCSS stylesheet file  
│  
├── compile_css.sh                    # Shell script to compile CSS  
├── run_server.py                     # Python script to run the server  
├── src/                               # Source folder  
├── .gitignore                         # Git configuration file  
├── LICENSE                            # Project license file  
├── README.md                          # Project documentation file  
└── SiteInternet.iml                   # IntelliJ project file  
```

## License #
This project use the MIT License. It is in the file "LICENSE". 
