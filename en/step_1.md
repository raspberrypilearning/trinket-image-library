The starter file has a library of useful images.

Click on the 'View and Add images' icon: 

![An icon shaped like a piece of paper with top right corner folded over and a mountain scene on the paper.](images/view-add-images.png)

Scroll through the image library and make a note of the file name of an image you would like to use in your mood board: 

![The image library with beetle.jpg file shown.](images/image-gallery.png)

Add your image to the `<main></main>` in `index.html` so that it appears on your mood board webpage:

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 32
line_highlights: 35
---

    <!-- The main content for the web page goes between the main tags -->
    <main>
      Lorem ipsum dolor sit amet. 
      <img src="beetle.jpg">
       
    </main>

--- /code ---

Right click on the image on your webpage and select `Copy image address`:

![The output area in trinket with large beetle image. The rightclick menu has an option selected to 'Copy image address'.](images/copy-image-address.png)

In a new browser window, go to [coolors.co](https://coolors.co){:target="_blank"} and select the `Tools` menu then `Image picker`:

![The coolors.co website with tolls selected from the top right corner. The 'Image picker' tool is highlighted in the drop down menu.](images/image-picker-menu.png)

Click on the `Browse image` button: 

![The browse image button.](images/browse-image-button.png)

Click on `URL` then paste the copied image address into the `Image URL` box. Click `OK`:

![The Select image box with URL selected and the image address for the beetle image copied in.](images/select-image-box.png)

Sample palettes are created from your image. You can use the `picked palette` slider to select which colour scheme you want to use:

![The picked palette slider is a third of the way across. The image is shown with hotspots showing where the colours have been selected from.](images/generated-image-palettes.png)

When you are happy with the palette, click on the dropdown arrow of the `Export palette` button and select `Open in the generator`:

![The Export palette menu with the top item 'open in the generator' selected.](images/generate-palette-menu.png)

The final palette will be shown. The coded letters and numbers are the hex codes for your chosen colours. Update the variable values in your `default.css` file to use these new colours:

![Squares of colour with the hex codes written on them.](images/final-image-palette.png)


--- code ---
---
language: html
filename: default.css
line_numbers: true
line_number_start: 4
line_highlights: 5-14
---

:root {
  --primary: #08586B;
  --onprimary:#4f4e4e;
  --secondary: #E0DB54;
  --onsecondary:#ffffff;
  --tertiary:#AF5C08;
  --ontertiary: #ffffff;
  --page:#ffffff;
  --onpage:#000000;
  --detail: #AB7C1C;
  --detail2: #38640D;
}

--- /code ---
