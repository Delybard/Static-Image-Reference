# Static-Image-Reference

## HOWTO
1) Copypasta the [`Index.html`](./Index.html) file to your project
2) Create an Images folder
3) Add your images to the Images folder. Best to rename them to something descriptive or simple like 1.png, 2.png, etc.
4) Open the [`Index.html`](./Index.html) file and copypaste the line with the `<img src="Images/1.png" alt="Image 1">` tag a few times and change the `src` attribute. You can, but don't need to, change the `alt` attribute too. If you want to add a third Image, then the new line would look like this for example: `<img src="Images/3.png" alt="Image 3">`
5) In your Repository, go to `Settings` -> `Code and automation` -> `Pages` and select as `Source` `Deploy from branch`, as branch select `main`, then `/ (root)` and now click `Save`. Building the Github Page can take a few minutes, don't worry if it doesn't appear right away. Once it is done it will show you the url to your github page at the top. In my case the url is: https://delybard.github.io/Static-Image-Reference/ - don't worry if it shows you a 404 Error when you visit it!
6) The URL for your images look like this: 
  * base url / folder name / image name with file extension: 
  * https://delybard.github.io/Static-Image-Reference/Images/1.png 
  * https://delybard.github.io/Static-Image-Reference/Images/2.png

7) If you want to change an image for your world, just replace the image in the Images folder with a new one. But consider that it can take a few minutes for the image to update on your Github Page

## URL for Images
Looks like this: base url / folder name / image name with file extension:  
https://delybard.github.io/Static-Image-Reference/Images/1.png  
https://delybard.github.io/Static-Image-Reference/Images/2.png
