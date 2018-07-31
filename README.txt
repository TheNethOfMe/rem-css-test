Hey Everyone!
I made a super cool REM fansite in HTML. Unfortunatley, it looks really bad without any styling.

Look at the instructions for how I want the site to look and pick out the css code block from the list that would 
best achieve the desired outcome without messing with anything else on the site. Keep in mind, only half of the 
possible code blocks will be used.

Check out the HTML in my github repo to make you decisions. And when you're done, you can look at my CSS 
file to see if your answers match mine. There's an answer key at the bottom of the css file.

1) I want to change the font to a san-serif font and center the text for the entire document.

2) I want all of the headings to be red except for the "Band History" heading.

3) I don't want bullets on the unordered list.

4) I need the tables to be centered with a nine pixel margin on the top and bottom.

5) I want the table with the band members to have borders around each cell.

6) I want the first year in the band facts area to be bold.

7) I want the two spans in Mike's table data to be green for some reason.

8) Let's have every other row on the discography table be shaded gray for readability but leave the heading white.

9) I want the songs that charted on the Billboard 100 to be red.

A) table {
    margin: 9px;
    text-align: center;
}

B) #facts table *:not(span) {
    border: 1px solid black;
} 

C) .overview span:first-child {
    font-weight: bold
} 

D) * {
    font-family: sans-serif;
    justify-content: center;
}

E) h1, h2, h3:not(.history) {
    color: red;
} 

G) tbody tr:nth-child(2n - 1) {
    background-color: #ccc;
} 

G) h1, h2, h3:not(:first-child) {
    color: red;
}

H) * {
    font-family: sans-serif;
    text-align: center; 
}

I) #hot-100 {
    color: blue;
}

J) ul {
    list-style-type: none;
} 

K) .hot-100 {
    color: blue;
} 

L) li {
    text-decoration: none;
}

M) #facts table * {
    border: 1px solid black;
}

N) #discography tbody tr:nth-child(2n - 1) {
    background-color: #ccc;
} 

O) span:first-child {
    font-weight: bold
}

P) td span {
    color: green;
} 

Q) p span {
    color: green
}

R) table {
    margin: 9px auto;
} 
