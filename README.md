# shiny-multiple-windows

This is a shiny app that demonstrates using two separate browser windows, one with plotting controls, and the other with the actual plot. 

Please refer to [this](https://groups.google.com/forum/#!topic/shiny-discuss/DNlnC3JGNBI) discussion on Google Groups.

The application requires the [shinyjs](https://github.com/daattali/shinyjs) library to be installed. 

The aim was to make the whole thing as transparent as possible to shiny. The approach is based on storing the image in the browser local storage and adding an event listener to the plot window that watches for modifications to the local storage and loads the image data from it.

