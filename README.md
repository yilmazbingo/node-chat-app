# node-chat-app
socket io

#installation of sass

Download Ruby because sass is written in Ruby. Open the “start command prompt with Ruby” and enter this:

    gem install sass

In macos, ruby is already installed. so in terminal:

    sudo gem install sass

If you did install bootstrap through package manager; write this code into main.scss

    @import "../node_modules/bootstrap/scss/bootstrap";

then navigate to your work directory where you keep your main.scss or main.css files. Enter this code into command line:

    sass main.scss main.css

this will initialize compiling sass to css.

If you did download bootstrap source files, find the “scss” folder in your source folder

    BOOTSTRAP\bootstrap-4.2.1\bootstrap-4.2.1\scss

and copy it into your style folder in your project where u keep all styling files:css,scss,bootstrap then import “bootstrap.scss” file into main.scss

    @import "./scss/bootstrap.scss";

And now initialize compiling by entering this code:

    sass main.scss main.css

Finally, you can type:

    sass --watch main.scss:main.css //this should be running

to watch all changes in main.css DONT FORGET: You will write your css codes into main.scss, sass will compile it to main.css and you will LINK main.css file in your html.

If you are using visual studio code, you can install “Live Sass Compiler” extension and down below you will see “Watch Sass” button. create main.scss file in the style folder and after import the files the way I explained above, click on the “watch Sass” button and it will start compiling.

  

