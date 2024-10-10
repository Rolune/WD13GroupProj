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