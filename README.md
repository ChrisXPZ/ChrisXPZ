[IMPORT]
importdb (NotReallyAProgrammer);

[README]
str Name = "@ChrisXPZ";
str Interests = "Video games, building PCs, repairing broken things, Graphics, playing with scripting languages, making custom configurations, playing around in linux.";
str Learning = "Arch Linux, Mac repair"; 
str Collaboration = ""; //looking for interesting things
str Email = "chrisxpz" && fn(PrintGmail());

[FUNCTIONS]
fun PrintGmail (append-str "@gmail.com");
fun PrintReadme (echo ("Name: " Name ->v "Interests: " Interests ->v  "Learning about: " Learning ->v "Collaborating on: " Collaboration ->v ->v "You can contact me at: " Email ->v "Please no advertising or solicitation.");

[START]
GetWindowInformation();
PrintReadme();

<!---
ChrisXPZ/ChrisXPZ is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
