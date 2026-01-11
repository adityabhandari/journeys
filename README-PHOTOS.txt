HOW TO ADD PHOTO BACKGROUNDS TO THE FLIGHT SCHEDULE
====================================================

The flight schedule visualization has been set up to display subtle photo backgrounds
for each traveler's journey section. Follow these steps to enable them:

STEP 1: Locate the Images
--------------------------
Two image files have been saved alongside the HTML file:
- luka.png (Luka's photo)
- aditya-ruchi.png (Aditya and Ruchi's photo)

STEP 2: Place Images in the Same Directory
-------------------------------------------
Make sure both PNG files are in the same directory/folder as the 
flight_schedule_v3.html file.

STEP 3: Enable the Photo Backgrounds
-------------------------------------
Open flight_schedule_v3.html in a text editor and find this section in the CSS
(around line 210):

    /*
    .luka-journey::before {
        background-image: url('luka.png');
    }

    .ar-journey::before {
        background-image: url('aditya-ruchi.png');
    }
    */

Remove the /* and */ comment markers to uncomment these rules.

STEP 4: Save and Open
----------------------
Save the HTML file and open it in your web browser. You should now see:
- Luka's photo as a subtle background (15% opacity) behind his journey timeline
- Aditya and Ruchi's photo behind their journey timeline

NOTES:
------
- The photos appear at 15% opacity so they don't interfere with readability
- Photos are positioned to cover the entire journey section
- All timeline elements, tables, and text remain clearly visible on top
- The background adds a personal touch while maintaining professional appearance

TROUBLESHOOTING:
----------------
If photos don't appear:
1. Verify image files are in the same folder as the HTML file
2. Check that file names match exactly: luka.png and aditya-ruchi.png
3. Make sure you uncommented the CSS rules correctly (no /* or */ remaining)
4. Try refreshing your browser (Ctrl+F5 or Cmd+Shift+R)
