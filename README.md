Download Link: https://assignmentchef.com/product/solved-st558-project-3-creating-a-shiny-app
<br>
5/5 - (1 vote)

The goal of this project is to create a nice looking shiny app that can be used to explore data and model it.

You should put your shiny app on your github account and simply post the link to the repository. We will run them from gitHub using RStudio so make sure it is set up correctly to do that (see lecture for reference to setting it up, try it yourself to make sure it works!).

Find a data set you are interested in

For this project I’m going to let you choose your own data set. You can either pull in a data set via a file or you could pull data from the web within your app (for instance baseball data (link) or twitter data (link)).

Choose something you are interested in and have ideas for investigating!

App Requirements

<ul>

 <li>Your app should have multiple pages (tabs) to it. I don’t care if you use the built in tabs for shiny or a package like shinydashboard – use the method you prefer.

  <ul>

   <li>–  An information page that describes the data and abilities of the app</li>

   <li>–  A data exploration page where common numeric and graphical summaries can be created by theuser</li>

   <li>–  A page with either clustering (include a dendogram) or principal components analysis (include a biplot) – again where the user can specify aspects of the algorithm</li>

   <li>–  A page for modeling – see below for details</li>

   <li>–  A page that allows the user to scroll through the data (or subset of data of interest)</li>

  </ul></li>

 <li>You should have at least two different dynamic UI elements.</li>

 <li>You should have a button that allows the user to save a plot they are viewing to a file.</li>

 <li>You should have an option to allow the user to save the data currently being used for a plot (or when they are looking at the data table) to a .csv (or other) file.</li>

 <li>You should utilize the ability to click on a plot or select a region in some way.</li>

 <li>You should include some type of math type (maybe an equation or just a special symbol you need to use mathJax for).</li>

 <li>You should include a link to something and some other formatted text.</li>

 <li>Modeling

  <ul>

   <li>–  (At least) two supervised learning models (feel free to branch out to things we didn’t discuss if you’d like)</li>

   <li>–  You should give the user some functionality for choosing model settings (variables used, number of trees, etc.) and for changing relevant output</li>

   <li>–  You should give the user a way to use the model for prediction (they should be able to select the values of the predictors).</li>

  </ul></li>

</ul>

1

Notes

<ul>

 <li>There are some nice shiny additions such as a status bar that you can add to display to the user that your model is running.</li>

 <li>Remember that most people that have apps make their code freely available (often on gitHub). One thing you might do is search through apps to find someone that say has the option to download the data set. Check their code on gitHub to see how they did it and if it makes sense for you. The openness of the R community is really one of the great benefits of using R!</li>

 <li>This project is pretty open ended! Have fun with it and make something that you can show off to others – Good luck &#x1f642;</li>