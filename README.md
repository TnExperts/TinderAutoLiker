# TinderAutoLiker
A tool to automatically like Tinder profile's.

# Instructions
1. Login into Tinder.com then right click Tinder in Google Chrome to "inspect" then click on the "Network" tab. 
2. Next find the X-Auth-Token under the "Network" tab by pressing F5. 
3. While in the "Network" tab find "core?=locale=en" and click on it to find your X-Auth-Token under Request Headers. 
4. Edit auto-like.py and insert your X-Auth_token and save the file. 
5. python3 auto-like.py
