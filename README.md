# NYC MTA Real Time Bus Tracking  (an MITxPRO Pacman Exercise)
## Project Title: ``MTA Bus Tracker``
## Description: 
``MTA Bus Tracker`` is an attempt to create an animation that displays a city bus location in real-time via an API to source real-time Bostom MBTA buses. The goal was to refactor a starter kit code created by MIT x PRO using NYC's live bus status. However, the animation was applied to Boston MBTA buses instead due to complexity of the NYC data.
 <br> </br>
## How to Run
•	You must download all files from this repository to your local drive. Run the index.html file on any source code editors (ie. VS Code) and preview your edits on HTML source viewer (ie. Google Chrome browser). <br>
•	You will also need to request an API key to the weather API, which has rate limiting of 60 requests per minute before being denied.
•	In the <br>mapanimation.js<br> file where the code says 'replace w your API key', replace the text with your personalized API key.

<br> </br>
This project includes 3 files: <br> 
•	<b>Index.html</b>: displays the html site where you can see the map bus tracker code visually <br>
•	<b>mapanimation.js</b>: includes the javascript programmed to run the animation that highlights the stops on the map <br>
•	<b>styles.css</b>: the styles for the map of Boston between Harvard and MIT <br>
 <br>
## Roadmap for Future Improvements
Future improvements for this project include: <br>
•	Fix bugs in the github version of this code - _currently triggers 404 whereas the code works on my localdrive_ <br>
•	Customize the map to fit NYC's concentrated traffic instead <br>
  -Create flags to indicate delays/early departures <br>
  -Indicate busy-ness on the bus  <br>
  -Change the color of each bus stop the bus has passed by <br><br>
•	Create several functions, such as: <br>
  -Send alerts to email and phone <br>
  -Send notification to the screen <br>
  
## Credit
MIT x PRO Full Stack Engineer Course which provided the starter kit to code this exercise

## License
Copyright (c) 2022 Claire Zhang

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
