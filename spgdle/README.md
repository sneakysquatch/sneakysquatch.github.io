# youtube-heardle-template

A template for a youtube link Heardle instead of soundcloud link [Heardle](https://www.heardle.app/), 


code edited from: [here](https://github.com/sarvarghese/heardle-template)
 <br /> 
 <br /> 
WIP - MAY HAVE BUGS/ISSUES


HOW TO MAKE YOUR OWN HEARDLE **(as of 4/27/22)**

1. Remix this project to create your own copy of the code ✅
2. Rename the project with the URL that you'd like to Heardle to live at ??
3. Open the **index.html** file & replace **"Joywave"** with the artist/genre of your heardle ✅
4. In the **index.html** file, you can update the image that gets shared with your link by updating the **href** tags as notes in the file. ✅

5. On line 2 of **main.js** file and update artist with the artist/genre of your heardle - This will update all the text boxes & titles where "Joywave" shows up
6. On line 3 of **main.js**, update the **startDate** to the current date in the format **MM/DD/YYYY** - This will start the counter for your Heardle
7. On line **17381** of **main.js**, "const **Bt**" is initialized. Here you'll have to replace the links with links to your songs.Each link will have to follow the following format:
   `{ arist: "artist name", name: "song name", youtubeId: "<youtubeId>" },`
8. To get the youtube id of a youtube link, click the **"Share"** button and copy the text after the **"youtu.be/"**, For example, in this link **https://youtu.be/TA5kvZ9aqDI**, the youtubeId would be **"TA5kvZ9aqDI"**

<br /> 
<br />

At the moment, the order of the songs match the order that the Heardle's will appear, so if you dont want to ruin the surprise, have someone else upload the order of the songs and links for you!

<br /> 
<br />

Glitch auto saves your code, so your changes should be available as soon as the code is editted
Heardle doesnt work in the "Open Preview Pane" option, so make sure to view it in the "Preview in new window" option


Feel free to tweet/dm me @joywavez on twitter if you have any issues/questions!

**KWOWN ISSUES**
- Stats are saved at the moment - still working on that
- Sometimes the play button doesnt work because the Youtube video might not be available.