# R-Programming
Hi Coders! \
I have hereby compiled a set of instructions for understanding the basics of R Programming language.

Before we begin, let's revisit some concepts.

So what is R ?

R is a dialect of the S programming language, written and developed by John Chambers in Bell Labs. R is a relatively recent development ( in 1991) , created in New Zealand by Ross Ihaka and Robert Gentleman.

## Installation:
There are three steps you need to follow in a sequential order:
1. **Install Perl** : Before installing R, make sure to install Perl first, becuase many of the libraries in R are written in Perl. If you are using Linux or macOS, your system already comes with Perl installed. For Windows, you need to install Perl separately. Follow this link for perl installation : https://www.perl.org/get.html
2. **Install R** :
   - For Windows : https://cran.r-project.org/bin/windows/base/
   - For macOS : https://cran.r-project.org/bin/macosx/
   - For Linux : Follow the appropriate command depending on your Linux version 
     
     `$ sudo apt install r-base`  - For Debian or Ubuntu
     
     `$ sudo dnf install R `   - For RedHat or Fedora
                                                                                                 
     `$ sudo pacman -S r `    - For Arch or Manjaro
                                                                                             
     `$ sudo zypper install R-base R-base-devel`    - For OpenSUSE

   After finishing the installation, 
4. **Install RStudio**
   To install R Studio, you can follow these general steps. Please note that the specific steps may vary slightly depending on your operating system (Windows, macOS, or Linux).

   - **For Windows:**
   Download R Studio from the official R Studio website: https://www.rstudio.com/products/rstudio/download/ Choose the free version (RStudio Desktop) that corresponds to your 
   operating system. Follow the installation instructions.
   - **For macOS:**
     Download R Studio from the official R Studio website: https://www.rstudio.com/products/rstudio/download/  Choose the free version (RStudio Desktop) that corresponds to your 
     macOS version. Follow the installation instructions.
   - **For Linux:**
     Install Dependencies for R Studio:
     R Studio has additional dependencies that you may need to install. For Debian/Ubuntu, you can use the following command:

     `sudo apt-get install gdebi-core`

     Download R Studio from the official R Studio website: https://www.rstudio.com/products/rstudio/download/
     Choose the free version (RStudio Desktop) that corresponds to your distribution.
     Open the terminal, navigate to the directory containing the downloaded file, and install it using the following command:

     `sudo gdebi rstudio-x.yy.zzz-amd64.deb`

After Installation:
Once R Studio is installed, you can open it, and it will prompt you to choose the version of R that you want to use. It will automatically detect the version you installed earlier.

You can then start working with R and R Studio for your statistical and data analysis tasks.

Remember to check the official R Studio documentation for any additional details or troubleshooting: https://support.rstudio.com/hc/en-us

