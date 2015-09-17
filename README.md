# Code Dark UI theme

A dark UI theme mixing **Atom Dark** and **Visual Studio Code** elements.

I created this theme mostly to unify my `styles.less` file that contained a few visual tweaks. And with **Visual Studio Code** launch, I  decided to apply some elements that I enjoyed, in **Atom**. So here it is :)

![Screenshot](https://raw.githubusercontent.com/alefragnani/atom-code-dark-ui/master/screenshot.png)

## Known Issue

The StatusBar is not working correctly. You must put this piece of code on your Stylesheet. To do so open `File / Open Your Stylesheet` and add this code.

    status-bar {
      position: fixed;
      bottom: 0;
      left: 0;
      right: 0;
      background-color: #007ACC;
      color: white;
    }

## Development Status

I'm new to CSS and LESS so you will find some bugs. The theme is _in early development_, so be patient :)
