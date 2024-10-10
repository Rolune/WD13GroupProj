Research Note
might be helpful

---

Looking into "only screen" 
https://stackoverflow.com/questions/8549529/what-is-the-difference-between-screen-and-only-screen-in-media-queries
seems like it's prevent bug in older machine
	backward compatibility
Leaving it in

---

grid-template-columns: repeat(auto-fit, minmax(450px, 20%));
doesn't work
I think you can't use percentage for minmax?
should use something like
grid-template-columns: repeat(auto-fit, minmax(450px, 1fr));

---

https://elharony.com/images-not-displaying-in-github-pages/
GitHub Pages is case-sensitive

Locally, it doesn’t matter. But if you are deploying your app on GitHub Pages, you have to double-check the sensitivity of the images’ name. Keep in mind;

    myImage.jpg isn’t the same as myImage.JPG
    Moreover, myImage.jpg isn’t the same as myimage.jpg
