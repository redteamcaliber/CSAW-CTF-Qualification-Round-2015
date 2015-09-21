Step 1:

This was my very first Recon challenge. The challenge tells you to start at fuzyll.com/csaw2015/start.

<img src='https://github.com/CYBR-AH/CSAW-CTF-Qualification-Round-2015/blob/master/Alexander%20Taylor/Step_1.png'>

Step 2: 
I need to find the acronym for his university's hacking club. After searching his LinkedIN, I saw Alex went to University of South Florida and he was president of the Whitehatters Computer Security Club (wcsc).

<img src='https://github.com/CYBR-AH/CSAW-CTF-Qualification-Round-2015/blob/master/Alexander%20Taylor/Step_2.png'>

Step 3:
This string is clearly base64 decode. I just pulled it into https://www.base64decode.org/ and decoded.

<img src='https://github.com/CYBR-AH/CSAW-CTF-Qualification-Round-2015/blob/master/Alexander%20Taylor/Step_3.png'>

Step 4:
For this part, I searched his handle on YouTube. Very first result, Yoshi.

<img src='https://github.com/CYBR-AH/CSAW-CTF-Qualification-Round-2015/blob/master/Alexander%20Taylor/Step_4.png'>

Now to test..

<img src='https://github.com/CYBR-AH/CSAW-CTF-Qualification-Round-2015/blob/master/Alexander%20Taylor/Step_4a.png'>

I downloaded Yoshi and opened with Notepad. Next challenge is to find the first cryptosystem Alex had to break at his first Def Con qualifier. I spent a lot of time roaming through 2011 and realized the answer was in 2010 Def Con Qualifiers (facepalm)

<img src='https://github.com/CYBR-AH/CSAW-CTF-Qualification-Round-2015/blob/master/Alexander%20Taylor/Step_4b.png'>

Answer Enigma

Step 5:

<img src='https://github.com/CYBR-AH/CSAW-CTF-Qualification-Round-2015/blob/master/Alexander%20Taylor/Step_5.png'>

I've never done any Javascripting before so I pulled this into w3schools and got the answer I needed.
I just added the string as 'var s' and added 'window.alert(c)'.

<img src='https://github.com/CYBR-AH/CSAW-CTF-Qualification-Round-2015/blob/master/Alexander%20Taylor/Step_5a.png'>

Look at the popup!
<img src='https://github.com/CYBR-AH/CSAW-CTF-Qualification-Round-2015/blob/master/Alexander%20Taylor/Step_5b.png'>


Step 6:
<img src='https://github.com/CYBR-AH/CSAW-CTF-Qualification-Round-2015/blob/master/Alexander%20Taylor/Step_6.png'>

Flag was at fuzyll.com/csaw2015/they_see_me_rollin. flag{I_S3ARCH3D_HI6H_4ND_L0W_4ND_4LL_I_F0UND_W4S_TH1S_L0USY_FL4G}
