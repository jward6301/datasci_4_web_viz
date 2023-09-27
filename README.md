# datasci_4_web_viz
HHA 507 Week 4 Assignment


## Visualization Links
1. R's Shiny Visualization link: https://k8a2hc-jward6301.shinyapps.io/shiny_r/
2. Python's Shiny Visualization link: https://k8a2hc-jward6301.shinyapps.io/your-app-name/

## Reflections
1. R's Shiny Visualization issues and challenges:
* I ran into issues connecting the Posit cloud to shinyapps.io. I ran tr R Shiny visualization last after running the python flask and shiny python. After running shiny python I had forgot that you needed to connect to Posit cloud to run the r code properly. I soon relized and uplaoded my repo to Posit. After trying to run the code provided and directions from https://docs.posit.co/shinyapps.io/getting-started.html#working-with-shiny-for-r, I kept receiving error codes such as Error in `checkAppLayout()`:. I realzied that I was doing steps that I did not need to complete to connect to shinyapps.io. Instead, I needed to publish it to the shinyapps.io website instead, which I found instuctions on how to do this through this link https://docs.posit.co/connect/how-to/publish-shiny-app/. Once publishing and connecting to my shinyapps account, it worked. 
* I also have limited experience using Posit cloud, so figuring it out did take some time. Running the python flask was much quicker due to experince running flask apps through cloud shell previously.  
2. Python's Shiny Visualization issues and challenges:
* I ran into issues when connecting to shinyapps.io. When trying to follow the steps from this website: https://docs.posit.co/shinyapps.io/getting-started.html#working-with-shiny-for-python i kept receving error codes of cannot connect or cannot locate. In order to properly connect, your shell directory has to be connected to the exact folder in the workspace. Once using cd to change to the correct folder, the codes started to work. I also ran into issues when running the following code rsconnect deploy shiny /path/to/app --name <NAME> --title my-app. I was unaware at first that the .py file name had to follow that code. I also had to make sure that there was a requirements.txt file for this to run properly. 
* A challenge I faced was remebering to pip install all new packages that I have not used recently.
3. Python Flask issues and challenges:
* No issues or challenges faced. 

The image to view the python flask deployment:
![Alt text](https://github.com/jward6301/datasci_4_web_viz/blob/main/Flask%20Screenshot.png)