Chapter 07 Finding the path

\1) What are the various ways to add image in our app? Explain all of them with coding?

- **Using the img tag**: Using the img tag we have to provide a 2 values.

`                                   `Src: The URL and the path of the imges.

`                                   `Alt: An alternate text if image is not available.

`                                   `Ex - <img src=” URL.jpg” alt= ”Logo” />

- **Setting a background image**: Using CSS we can add the image in our app.

`                                `**Ex** .app {

`                                                        `Background-image: url(“logo.jpg”);

`                                              `}

- Structuring our code: Just create a image folder in your app and put your image on that folder.

`                               `![https://miro.medium.com/max/616/1\*w-It64F8UdogZsRtitqrzQ.png](Aspose.Words.f6a86aef-0295-48c7-9d5b-f7e194a802e3.001.png)

\2) How will useEffect behave if we don’t add any dependency on it?

`               `If we don’t add any dependency on useEffect hook it will render every time whenever our component is doing something.

\3) What is SPA?

`             `Single Page Application (SPA) is a web app implementation that’s load only single web document and then updates the body content of that single document.

\4) What is the difference between client side routing and server side routing?

`             `Server side routing you download an entire new webpage whenever you click on a link and reload your pages. 

`             `Client side routing the webpage download, processes and display new data for you it will not reload your pages.

\5) What would happen if we do console.log( useState() )?

`             `It would return a array which contains two value 1) the value which we passed when we are declare a variable either it would pass undefined and 2) It would call a function whenever we have to update our local state variable. 
