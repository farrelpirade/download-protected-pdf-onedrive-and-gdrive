Onedrive protected pdf 

ONLY TESTED ON WINDOWS USING GOOGLE CHROME AND POWERSHELL

WATCH THE VIDEO IF YOU DON'T WANT TO READ THE ENTIRE FILE, IT'S THE SAME

video link : https://drive.google.com/file/d/1g1o7Eclt7P6Qg_dXlPeqwQEfudfxTsiD/view?usp=sharing

Tutorial : 

1. Open the pdf (can be from the view only folder or even from the link you get)

2. Open Developer Tools (F12 on your keyboard)

3. Open the Network section

4. Hit Refresh page

5. there will be bunch of packets, sort them from size

6. Usually, the pdf package is the one with the keyword "passthrough" , search for it

7. right click on the package, click copy as powershell

8. open notepad and paste it all there

9. paste the script at the end (THE TICK MUST BE AT THE VERY END OF THE LAST CHARACTER FROM THERE, NOT FROM A NEW LINE)

script you can paste at the end of copy as powershell : 

`

-OutFile "$env:USERPROFILE\Downloads\document.pdf"

10. copy it all (the document.pdf part can be changed to whatever name for the doc you want, JUST DON'T CHANGE THE .pdf PART)

11. open powershell (normal or admin mode, both ok)

12. paste it all, yeah and hit the enter button

13. just wait and be patient

14. after it's done, check your download folder

15. voila!
