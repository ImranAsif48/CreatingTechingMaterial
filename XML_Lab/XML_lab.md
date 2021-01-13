# XML Lab

## 1) Create a Valid XML document

Open a text editor like Notepad++, Atom, GEdit, or Visual Studio Code. (Code editors provide syntax highlighting for XML, making it easier to understand your work.)

Create an XML document which stores the following data about films. It’s a good idea to save the XML to a file on your drive (e.g films.xml) before copying the text to the web link below. 

### FILMS:

| Title               | Classification | Stars                                                | Genre                                 |
| ------------------- | -------------- | ---------------------------------------------------- | ------------------------------------- |
| Joker               | R              | <ul><li>Joaquin Phoenix</li><li>Robert De Niro</li></ul>                  | <ul><li>Crime</li><li>Drama</li><li>Thriller</li></ul>        |
| Singing in the Rain | G              | <ul><li>Gene Kelly</li><li>Donald O’Connor</li><li>Debbie Reynolds</li></ul> | <ul><li>Comedy</li><li>Musical</li><li>Romance</li></ul>      |
| The Lion King       | PG             | <ul><li>Donald Glover</li><li>Beyonce</li><li>Seth Rogen</li></ul> | <ul><li>Animation</li><li>Adventure</li><li>Musical</li></ul> |

Create your XML document following this template:

```xml=
<?xml version="1.0" encoding="UTF-8"?>
<films>
    <film>
    	<title>...</title>
	...
    </film>
</films>
```


### Check your XML

Use a web browser to open the [W3 Schools XML Validator](https://www.w3schools.com/xml/xml_validator.asp).

Scroll down the page to the `Syntax-check Your XML` section and copy/paste your XML to validate it. If there is an error in the XML then check the debug information, and correct the XML. 

Once you have completed this task you can close this webpage and your file.

## 2) XPath

We’ll now take a look at using XPath to filter an XML document with information about music albums as follows:

| Artist     | Album Title               | Genre     | Released Date | Bookmarked Tracks                                 |
| ---------- | ------------------------- | --------- | ------------- | ------------------------------------------------- |
| Bill Evans | The Bill Evans Album      | Jazz      | 1971          | <ul><li>Sugar Plum</li><li>Waltz for Debby</li></ul>                   |
| Queen      | Jazz                      | Rock      | 1978          | <ul><li>Don't Stop Me Now</li></ul>                                 |
| Jamiroquai | Travelling Without Moving | Acid Jazz | 1996          | <ul><li>Virtual Insanity</li><li>Cosmic Girl</li><li>High Times</li></ul> |
| Muse       | Drones                    | Rock      | 2015          | <ul><li>Reapers</li><li>The Handler</li></ul>                         |

This dataset is available to download in XML from [here](f21df.xml). 

Take a look at the XML document structure:

```xml=
<?xml version="1.0" encoding="UTF-8"?>
<albums>
    <album>
        <artist>...</artist>
        ...
    </album>
</albums>
```

Copy across the XML data and write your XPath answers to the following questions. You can use the following online service to test your xpath queries https://www.freeformatter.com/xpath-tester.html.

### Queries

1. Get all the album titles
1. Show the artist for the last album on the list
1. Show all the details for the `'Jazz'` genre albums
1. Show the album title for those released before 1980 (not inclusive of 1980)
1. Show the bookmarked tracks for all `'Rock'` genre albums
1. Show a COUNT of how many bookmarked tracks there are in total
1. Show the album title for records where 2 or more tracks have been bookmarked
1. Show a list of the album titles which include the word `'Album'` in the title
1. Show a list of the album title and artist with the 'Rock' genre

   

### Resources:

Check the lecture notes for examples of XPath. You may also find the [W3 Schools XPath Tutorial](https://www.w3schools.com/xml/xpath_syntax.asp) helpful.
