

HackerTest.net is your own online hacker simulation. 
With 20 levels that require different skills to get to another step of the game, this new real-life imitation will help you advance your security knowledge.
HackerTest.net will help you improve your JavaScript, PHP, HTML and graphic thinking in a fun way that will entertain any visitor!
Have a spare minute? Log on! Each level will provide you with a new, harder clue to find a way to get to another level.
Will you crack HackerTest.net?_

-----------------------------
## Level 1

- Level 1 as starting point to the next 20 levels in this challenge.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/1.png)


- If we inspect the code at the form, we will get `javascript:check()` action.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/2.png)


- So, let jump to `check()` function and we get `var a = “null”`. If we input “`null`” as the password, it will bring us to `http://www.hackertest.net/null.htm`, else it will popup alert as “`Try again`” as below.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/3.png)


- Here we are XD.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/4.png)

-----------------------------
## Level 2

- In level 2, just inspect the `null.htm` as before. Reviewing the javascript code, the `pass==”l3l”` and it will bring us to next level.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/5.png)

-----------------------------
## Level 3

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/6.png)


- For level 3, in js code there a method called `String.fromCharCode()`. The `fromCharCode()` method converts Unicode values into characters.
- **Note:** This is a static method of the String object, and the syntax is always `String.fromCharCode()`. Then, just simply decode the Unicode values online.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/7.png)


- There, we get “`abrae`” as output. then just go to `http://www.hackertest.net/abrae.htm` to next level.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/8.png)

-----------------------------
## Level 4

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/9.png)


- In level 4, clicking the “`Click here`” will bring us to `sdrawcab.htm`, so let us inspect it.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/10.png)


- As easy as l0l, it just giving us the password for level 5.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/11.png)

-----------------------------
## Level 6

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/12.png)


- As for level 6, the script will check the password from `psswd.js` file as below.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/13.png)


- By refering to `psswd.js` lead us to `var pass` as below. Voilla..

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/14.png)

-----------------------------
## Level 7

- In this level, we get login page. It is an authentication challenge.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/15.png)


- By login with random credential, it brings us to `pwd2.php` site. After inspecting it, there’s nothing interesting there.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/16.png)


- Let come back to main page. Walaoo, there’s nothing about javascript here but there is only one thing that caught my eyes. What’s that? It is `included.gif` hehe..By seeing with only one eye, we don’t think it is suspicious right? I’m stuck here for 3 minutes hahahaha… 

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/17.png)


- After browsing to `site/images/included.gif` route us to a big white image. Do you see what I see?? Once again, please look at the gif with ***4x optical zoom*** of your eyes hahaha.. Damn..super ~~tiny credential~~ at the right bottom there… almost ignore the tiny black credential there.
-  *It’s like our lives. We only focus on things in front of our eyes. We don’t see the good sides of people at whole things instead of pointing to their single mistake at only one single place*

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/18.png)

-----------------------------
## Level 8

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/19.PNG)

- As same as level 7, it’s a background gif named `phat.gif` with a clue of `Look for a .PhotoShopDocument!`
- It is `.PSD` right? A .PSD file is a layered image file used in Adobe PhotoShop. PSD, which stands for Photoshop Document, format that Photoshop uses for saving data.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/20.PNG)

- I think the .PSD file would be in the images directory, but it’s a nice try? Nahh….

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/21.PNG)

- Wait, it is .PSD file, right? What about `phat.psd`? Gotchaa. It gives us a file named phat.psd. Lets open it with [pixlr online photo editor]([https://pixlr.com/editor/](https://pixlr.com/editor/)).

- Too many Watermarks!!! here.. Remove them and you get the flag…

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/22.PNG)

- here the flag is !!

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/23.PNG)

-----------------------------
## Level 9

- Crack the password??

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/24.PNG)

- Inspect will give us hint `<!-- SOURCE CODE IS NOT AVAILABLE AT THIS TIME //-->`. Let's dig deeper.
- At the end of the source code, there's a hint of :
`<!---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------  Password: Z2F6ZWJydWg= add a page extention to that  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ >`

- It's base64 right? Decode `Z2F6ZWJydWg=` gives us `gazebruh`.
- It stated that we need to add page extension to that. Just add `.php` and got it to next level.

-----------------------------
## Level 10

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/25.PNG)

- The login page already reveal the hint. lmao `You will need to enable cookies for the Hacker Test Admin Panel to work as expected.`
- By login with wrong password we will get `If you are looking in the script, you are too far, go back.` So, it's not about javascript..Let's try cookie..
- Nah, not cookie also..
- But, there's suspicious in between 23 to 32 lines in below image. What's that? Ya, the italic letters. Let's combine them as password and get `Shackithalf`.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/26.PNG)

- At first we get nothing then try `shackithalf` as lowercase form and the login form suddenly missing! Check the source code out until we find the flag `<font color="#FFFFFF">Level 11: rofl.php</font>`. No wonder we dont see the flag as it is #FFFFFF HEX white font color.

-----------------------------
## Level 11

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/27.PNG)
- In the source code nothing interesting but `<meta name="robots" content="goto: clipart.php">`. We done..

-----------------------------
## Level 12

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/28.PNG)

- hint, `3 letters change everything. Look carefully!`
- In the source code, there's hint of `<meta name="clue" content="use graphic software">`
- So, it must related to graphic file...Let's try search for any image. 
- We find `logo.jpg` and inspect it lead us to `<img style="-webkit-user-select: none;margin: auto;cursor: zoom-in;" src="http://www.hackertest.net/images/logo.jpg" width="152" height="73">`. It is obvious of **cursor: zoom-in;**
- Zoom in and we get the flag... Do you see that?? 

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/29.PNG)

-----------------------------
## Level 13

- Hint, `Same thing, only different. Pay attention to the changes!`

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/30.PNG)

- We find `lvl13.gif` and zoom in we get `4.xml`.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/31.PNG)

- Oh, it's xml file. Reviewing it we get flag `4xml.php` as below image.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/32.PNG)

-----------------------------
## Level 14

- Hint, `Once again, same thing! Pay attention to the changes! A stupid person will wait 20 minutes to get an answer, a smart person will animate.`

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/33.PNG)

- The different between previous challenge is just `bidvertiser.gif`. It is a gif, so i should be animated right? Just animate it with [gif player online](https://onlineimagetools.com/gif-player) then get the flag. Damn easy! it is `totally.php`.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/34.PNG)

-----------------------------
## Level 15


- Hint, `Since you still have your photoshop open, check this out: [images/pass2level16.jpg](http://www.hackertest.net/images/pass2level16.jpg) << good luck with it!`

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/35.PNG)

- When we download and try to open it, it will fail...There's something corrupt or wrong file extension format..
- Ez, just open it with [Hexed.it](https://hexed.it/) and get the flag `unavailable` as below.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/36.PNG)

----------------------------------------------
## Level 16

- When we browse to `http://www.hackertest.net/unavailable/`, we will get source code as below.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/37.PNG)

- It is images directory. Browse to `http://www.hackertest.net/unavailable/images/` bring us to `background="bg.jpg"`.
- Download `bg.jpg` and open in [Hexed.it](https://hexed.it/) and get the flag `Ducky.php` at beginning of the file.

----------------------------------------------
## Level 17

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/38.PNG)

- View the source code get us a hint of `Password: your IP address`
- Then insert our public IP address and get hint of `../level18.shtml`.

----------------------------------------------
## Level 18

- Hint, `Think like a n00b.`
- There's also error message at bottom of the page, `$pass) { $errormsg=$msg; show_login_page($errormsg); exit(); } else { setmycookie(); } } else { if ($_COOKIE[$cookiename]<>$pass) { show_login_page($errormsg); exit(); } else { // do nothing } } ?> /level19.shtml << told ya to think like a n00b!!!`
- It's spill out the flag, `/level19.shtml` 

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/39.PNG)

----------------------------------------------
## Level 19

- Hint, `A little different, but still the same :)`

- View the source code give us `background="images/level20_pass.gif`
- 

    <table border="0" cellpadding="0" cellspacing="0" style="border-collapse: collapse" bordercolor="#111111" width="100%" id="AutoNumber4">
      <tbody><tr>
        <td width="100%" background="images/level20_pass.gif">
        <p align="center">A little different, but still the same :)  </p></td>
      </tr>
    </tbody></table>

- Same as level 14. It is a gif, just animate it with [gif player online](https://onlineimagetools.com/gif-player) then get the flag. Damn easy! it is `gazebruh2`.

----------------------------------------------
## Level 20

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/40.PNG)

- By reviewing the source code hint, 
- 

    <font face="Arial" size="2">
    VldwSk5Gb3lVa2hQUjJSclRUSlJlbFJITlU5TlIwNTBWbTE0YTFJelVqSlpNakF4WWtkT2NFNVlWbUZYUmtZeVYycEtTbG95U25SUFZFNU5Xbm93T1QwOT09<br>
    <font color="#FFFFFF">&nbsp;^^^^^^^^^^ Change domain, add "22332" at the end, reach it and then get hold of ... ^^^^^^^^^^ </font></font>

- First hint is  `Change domain, add "22332" at the end, reach it and then get hold of ... ^^^^^^^^^^`
- Second hint is `VldwSk5Gb3lVa2hQUjJSclRUSlJlbFJITlU5TlIwNTBWbTE0YTFJelVqSlpNakF4WWtkT2NFNVlWbUZYUmtZeVYycEtTbG95U25SUFZFNU5Xbm93T1QwOT09` that's seems like **Base64  hash digest**. 
- After *4x Base64 decode* we will get output as `Go to www.streetkorner.net/gb now.`
- Nothing in `www.streetkorner.net/gb`. But the first hint say that we must change the domain and add "22332" at the end. So it will be `http://www.hackertest.net/gb22332/` as below and we get error message of  `The requested URL /gb22332/login.php was not found on this server. Additionally, a 505 Not Found error was encountered while trying to use an ErrorDocument to handle the request.` hmmm

- Let's browse to http://www.hackertest.net/505/ and we have `The requested URL /505 was not found on this server.Additionally, a 403 Not Found error was encountered while trying to use an ErrorDocument to handle the request.`
- Then, browse to http://www.hackertest.net/505/403 and we get 
-

    <center><b>What is the answer to life, the universe, and everything?</b></center>
    <br><br><br>
    
    <!-- Add a file extension to that -->
- Googling that give us `42` as the answer... What??
- In Douglas Adams' sci-fi series "The Hitchhiker's Guide to the Galaxy," a pair of programmers task the galaxy's largest supercomputer with answering the ultimate question of the **meaning of life**, the universe and everything. After 7.5 million years of processing, the computer reaches an **answer**: 42

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/42.PNG)

- So, we have http://www.hackertest.net/42.php after adding file extension.

![enter image description here](https://raw.githubusercontent.com/faisalfs10x/faisalfs10x.github.io/master/asset/hackertest/44.jpg)


   Congratulations!  
      You have now cracked the HackerTest.net!  
      Secret code: seoJimWseo.  
      Great job, Well done.
