# ISW Registration Script

New Install (Windows)

Step 1: Install Python
* Download from python.org/downloads (last tested with 2.7.11)
* Install from download. If version 2.x, install location should be c:\python27 
* Add python path to system path
* * Control Panel > System and Security > System
* * Advanced System Settings > Environment Variables
* * System Variables > Path > Edit..
* * Add the following: ;c:\python27\
* * Hit OK three times
* Install 'csvkit'
* * at the Command line: 
*       pip install csvkit

Step 2: Copy ISW-registraiton-script folder
* Recommend: save entire directory in c:\

Step 3: Running the Python server and Loading the User Interface

1. From Terminal or Windows Command line:  Go into the 'isw-registration-script' directory

        cd isw-registration-script

2. Run the script:

        python isw.py
        
3. Open your favorite web browser and go to ((Double check the url listed after running the command below)):

        localhost:8080 
