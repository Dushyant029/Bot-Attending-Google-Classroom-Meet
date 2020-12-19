# Bot-Attending-Google-Classroom-Meet
This bot attends the meetings/online classes held on Google Classroom.

## Configure
Few things you need to configure before running the bot.

* Open AutoSignIn.py and put your Google Classroom credentials.
* For Eg:- `username.send_keys('Your Email ID'), username.send_keys('email@email.com')` similarly `password.send_keys('Your Password'), password.send_keys('12345')`
* Change the meet link as per ur course by 
   - Select the LINK -> Inspect -> Right Click on the Highlight Area -> Move on to Copy -> Copy XPath
   - Paste the code in     link = driver.find_element_by_xpath('`//*[@id="yDmH0d"]/div[2]/div[2]/div[1]/div/div[2]/div[2]/div/span/a/div`').
* Run it and Enjoy the class.   

## Install

 - Clone the repository `git clone https://github.com/Dushyant029/Bot-Attending-Google-Classroom-Meet.git`
 - Install 'pip selenium'.
 
