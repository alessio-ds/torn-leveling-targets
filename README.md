# Torn Leveling Targets
This tool allows you to search our faction database of 1800+ targets which are mostly inactive players, useful as leveling targets because we know their stats haven't changed from the original spy report.

I coded it in Python (and compiled it into an exe), but at the moment I don't feel like sharing the database for free.

![](https://i.imgur.com/Uy2DPSN.png)


# How to install:



### **Windows**:
**Download the latest build [here](https://github.com/alessio-ds/torn-leveling-targets/raw/main/TLT.exe)**

I compiled it with [autopytoexe](https://pypi.org/project/auto-py-to-exe/).
It will take some time to load (about 5 seconds).

### **Python** (don't want to share at the moment, maybe in the future):
You will need to install the [requests](https://pypi.org/project/requests/ "requests") library, by typing in your console:

`pip install requests`


# How to use:
It will ask for 3 things: 

- Max stats of your targets

- Quantity of targets to display

- If you want to include active players (press enter to say NO)

Depending on the quantity of targets you pick, it will take more or less time.



**Warning!**

When you download the .exe, your browser might detect it as a virus. It usually happens with programs that have got too few downloads.
The [VirusTotal Scan](https://www.virustotal.com/gui/file/a34ffe2084cd7e1b40100d5a164e34b365cde27e456f61794dc71c3b19babf48/detection) shows that it's not harmful, at best it gets detected as a "Heuristic threat". 
This is a common thing happening when using [autopytoexe](https://pypi.org/project/auto-py-to-exe/) to convert python files to exe.
