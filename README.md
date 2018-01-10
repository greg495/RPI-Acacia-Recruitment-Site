# rush-rpi-acacia.org
This is a recruitment website that I built for my college fraternity chapter. It was done as a final project for the class Fundamentals of Website Design. I took the class in Summer of 2016, thus the composite photos of the brothers are outdated, though it still shows the general concept. Our chapter was unfortunately never able to go live with this site, due to a lack of budget for hosting.
# Pages
Home Page: 
This contains general info about the chapter, several links to external pages, campus map, recruitment event schedule, phone numbers for the president and recruitment chair. Much of this info is available on the recruitment calendars that we give out to prospective members. Clicking on the link "view some of our rush photos from previous years" brings up an image carousel, run by the JavaScript library Swipebox.

Meet the Brothers:
Gives info about each of the active brothers, including their name, composite photo, roll number, year and major, position in the house, and any other extracurriculars that they do. This page makes use of the JavaScript library HandleBars to display this info from a JSON file using an HTML template, but because of that cannot be viewed locally from the HTML file in a browser, as HandleBars must be processed by a web server to display correctly. If viewed locally, it simply says Loading... but never does.

Philanthropy:
Acacia's motto is "human service," and as such we do several different philanthopy activities. This page displays some of them, including TASP, Moxie's Ice Cream, AcaciaStock, and Relay for life.

404 Error:
Shows a humorous photo of chapter cat, Anaximander, lost in space. This, too, requires a web server to actually display for a 404 error, however it can be viewed directly from the local HTML file.
