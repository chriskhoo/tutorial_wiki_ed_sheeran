# tutorial_wiki_ed_sheeran
Basic HTML CSS exercise to build a wiki page

## Instructions to recreate the HTML page:
Click [here](https://chriskhoo.github.io/tutorial_wiki_ed_sheeran/) to see the final page as a reference.
The exercise is to practice the HTML and CSS you've just learnt by recreating the page:
1. Copy the HTML boiler plate section
2. Copy and paste the text in the "text used" portion into the relevant sections
  * Header, Article, Aside
  * Slot the information text into tables
3. Add the appropriate HTML tags for the following:
  * For the header, there should 3 tags h1, hr, p  
4. In the article section:
  * Add a tag in the first line that helps bring the boldness of his name
  * Add emphasis to the mentions of albums ( No. 5 Collaborations Project, + , Red, x, ÷)
  * The anchor tags for Talyor Swift
5. In the aside section:
  * headers for Ed and the title of the table
  * The image tag for ed's face
  * Use a p tag for the image caption
  * Don't forget the anchor tag for Ed's website

## HTML Boiler Plate
Copy the code into the HTML portion of https://repl.it/
```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Ed Sheeran</title>
        <link href="index.css" rel="stylesheet" type="text/css" />
    </head>
    <body>
        <header>

        </header>

        <article>

        </article>
        <aside>

            <table>
                <tr>
                    <td class="row_head">
                    </td>
                    <td>
                    </td>
                </tr>
            </table>
        </aside>
    </body>
</html>


```
## Texted used
For your convenience, we've supplied the text used to generate this page.

```
Ed Sheeran

From Wikipedia, the free encyclopedia

Edward Christopher "Ed" Sheeran (born 17 February 1991) is an English singer-songwriter, guitarist and record producer. He was born in Halifax, West Yorkshire, and raised in Framlingham, Suffolk. He attended the Academy of Contemporary Music in Guildford, Surrey, as an undergraduate from the age of 18 in autumn 2009. In early 2011, Sheeran independently released the extended play, No. 5 Collaborations Project, which caught the attention of Elton John and Jamie Foxx. After signing with Asylum Records, his debut album, + (read as "plus"), was released on 9 September 2011 and has since been certified seven-times platinum in the UK. The album contains the single "The A Team", which earned him the Ivor Novello Award for Best Song Musically and Lyrically. In 2012, Sheeran won the Brit Awards for Best British Male Solo Artist and British Breakthrough Act.

Sheeran's popularity abroad began in 2012. In the US, he made a guest appearance on "https://en.wikipedia.org/wiki/Taylor_Swift" Taylor Swift's fourth studio album, Red. "The A Team" was nominated for Song of the Year at the 2013 Grammy Awards, where he performed the song with Elton John. He spent much of 2013 opening for Swift's The Red Tour in North America dates. In late 2013, he performed three sold-out shows at New York's Madison Square Garden as a headline act.

His second studio album, x (read as "multiply"), was released on 23 June 2014. It peaked at number one in the UK and the US. In 2015, x won the Brit Award for Album of the Year, and he received the Ivor Novello Award for Songwriter of the Year. His single from x, "Thinking Out Loud", earned him two Grammy Awards at the 2016 ceremony: Song of the Year and Best Pop Solo Performance. As part of his world tour, Sheeran played three sold-out concerts at London's Wembley Stadium in July 2015, his biggest solo shows to date.

Sheeran's third album, ÷ ("divide"), was released in March 2017. The album debuted at number one in the UK, the US and other major markets. The first two singles from the album, "Shape of You" and "Castle on the Hill", were released in January 2017 and broke records in a number of countries, including the UK, Australia and Germany, by debuting in the top two positions of the charts. He also became the first artist to have two songs debut in the US top 10 in the same week. Sheeran appeared on Debrett's 2017 list of the most influential people in the UK.

Ed Sheeran

"https://upload.wikimedia.org/wikipedia/commons/thumb/5/55/Ed_Sheeran_2013.jpg/440px-Ed_Sheeran_2013.jpg" "Ed's face"

Sheeran performing in Sydney, Australia, February 2013

Background information

Birth name
Edward Christopher Sheeran

Born
17 February 1991 (age 26)
Halifax, West Yorkshire,
England

Origin
Framlingham, Suffolk, England

Genres
Pop folk | pop | acoustic

Occupation(s)
Singer-songwriter, record producer, guitarist

Instruments
Vocals | guitar

Years active
2004–present

Lables
Asylum | Atlantic | Elektra

Website
"www.edsheeran.com" www.edsheeran.com
```

## Instructions for recreating the CSS
Instructions
1. Link your CSS file to the HTML page!
2. Check by changing the text to red
3. Now change the text to a more normal color like dark grey (#2e2e2e)
4. Next let's create 2 sections next to each other, the article and the aside. You'll need to:
  * change display to inline-block
  * set the width
  * set the vertical-align to top
5. For the side panel, let's:
  * create a solid grey boarder of 2px
  * give it some padding ~ 5px
6. Now let's fix the face:
  * set a class for the image
  * give it a relative width
  * change the display block
  * try this neat trick for centering divs: margin: 0 auto;
7. Now for the caption below it:
  * set a class for captions
  * align the text to the center using this text-align: center;
  * make the font size smaller (3/4 of the standard size)
8. In the table:
  * using the class row_head, bold the headers for each row
9. Lastly let's fix the headers in the side column:
  * Give it a yellow background (#f0e68c)
  * Make it slightly bigger than the normal (1.3 times the standard)
  * Align the text to the center
