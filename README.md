## Olympic Record

* [General info](#general-info)
* [Technologies](#technologies)
* [Contents](#content)

## General Info
This browser based web application is used to help fans track their favourite athletes throughout the games. Features will include favoriting athletes, checking the events they are participating in, their performance, and photo highlights from when they were competing. 
	
## Technologies
Technologies used for this project:
* HTML, CSS
* JavaScript
* Bootstrap 
	
## Content
Top level of the project folder:
│   .firebaserc             
│   .gitignore              # git ignore file
│   404.html                # 404 redirect page generated by firebase hosting
│   Alpine Skiing.html      # page shows specific event information on the Alpine Skiing Event
│   Athletes.html           # Page shows all athletes in the database
│   events.html             # Page shows all events in the database
│   favourites.html         # page shows all events and athletes the user has favorited
│   Figure Skating.html     # page shows specific event information on the Figure Skating Event
│   firebase.json           
│   firestore.indexes.json
│   firestore.rules
│   git
│   highlight.html          # page shows photo highlights of athletes that the user has favorited
│   Himari.html             # Athlete profile page for Himari 
│   index.html              # Landing page to login to the app
│   Janice.html             # Athlete profile page for Janice
│   Joo Hyuk.html           # Athlete profile page for Joo Hyuk
│   loading.html            # Page contains firebase authenticator, to login to the app
│   main.html               # Main page after logging into the app
│   README.md               # Contains information on all files in the source code folder
│   Scott.html              # Athlete profile page for Scott
│   Shawn.html              # Athlete profile page for Shawn
│   Snowboarding.html       # Page shows specific event information on the Snowboarding Event
│   Speed Skating.html      # Page shows specific event information on the Speed Skating Event
│   Tessa.html              # Athlete profile page for Tessa
│
├───.firebase
│       hosting..cache
│
├───assets
│   ├───css
│   │       style.css
│   │
│   ├───js
│   │       main.js
│   │
│   └───vendor
│       ├───animate.css
│       │       animate.compat.css
│       │       animate.css
│       │       animate.min.css
│       │
│       ├───bootstrap
│       │   ├───css
│       │   │       bootstrap-grid.css
│       │   │       bootstrap-grid.css.map
│       │   │       bootstrap-grid.min.css
│       │   │       bootstrap-grid.min.css.map
│       │   │       bootstrap-grid.rtl.css
│       │   │       bootstrap-grid.rtl.css.map
│       │   │       bootstrap-grid.rtl.min.css
│       │   │       bootstrap-grid.rtl.min.css.map
│       │   │       bootstrap-reboot.css
│       │   │       bootstrap-reboot.css.map
│       │   │       bootstrap-reboot.min.css
│       │   │       bootstrap-reboot.min.css.map
│       │   │       bootstrap-reboot.rtl.css
│       │   │       bootstrap-reboot.rtl.css.map
│       │   │       bootstrap-reboot.rtl.min.css
│       │   │       bootstrap-reboot.rtl.min.css.map
│       │   │       bootstrap-utilities.css
│       │   │       bootstrap-utilities.css.map
│       │   │       bootstrap-utilities.min.css
│       │   │       bootstrap-utilities.min.css.map
│       │   │       bootstrap-utilities.rtl.css
│       │   │       bootstrap-utilities.rtl.css.map
│       │   │       bootstrap-utilities.rtl.min.css
│       │   │       bootstrap-utilities.rtl.min.css.map
│       │   │       bootstrap.css
│       │   │       bootstrap.css.map
│       │   │       bootstrap.min.css
│       │   │       bootstrap.min.css.map
│       │   │       bootstrap.rtl.css
│       │   │       bootstrap.rtl.css.map
│       │   │       bootstrap.rtl.min.css
│       │   │       bootstrap.rtl.min.css.map
│       │   │
│       │   └───js
│       │           bootstrap.bundle.js
│       │           bootstrap.bundle.js.map
│       │           bootstrap.bundle.min.js
│       │           bootstrap.bundle.min.js.map
│       │           bootstrap.esm.js
│       │           bootstrap.esm.js.map
│       │           bootstrap.esm.min.js
│       │           bootstrap.esm.min.js.map
│       │           bootstrap.js
│       │           bootstrap.js.map
│       │           bootstrap.min.js
│       │           bootstrap.min.js.map
│       │
│       ├───bootstrap-icons
│       │   │   bootstrap-icons.css
│       │   │   bootstrap-icons.json
│       │   │   index.html
│       │   │
│       │   └───fonts
│       │           bootstrap-icons.woff
│       │           bootstrap-icons.woff2
│       │
│       ├───boxicons
│       │   ├───css
│       │   │       animations.css
│       │   │       boxicons.css
│       │   │       boxicons.min.css
│       │   │       transformations.css
│       │   │
│       │   └───fonts
│       │           boxicons.eot
│       │           boxicons.svg
│       │           boxicons.ttf
│       │           boxicons.woff
│       │           boxicons.woff2
│       │
│       ├───glightbox
│       │   ├───css
│       │   │       glightbox.css
│       │   │       glightbox.min.css
│       │   │
│       │   └───js
│       │           glightbox.js
│       │           glightbox.min.js
│       │
│       ├───isotope-layout
│       │       isotope.pkgd.js
│       │       isotope.pkgd.min.js
│       │
│       ├───php-email-form
│       │       validate.js
│       │
│       ├───purecounter
│       │       purecounter.js
│       │
│       ├───swiper
│       │       swiper-bundle.min.css
│       │       swiper-bundle.min.js
│       │
│       └───waypoints
│               noframework.waypoints.js
│
├───css
│   │   animate.css
│   │   bootstrap.min.css
│   │   style.css
│   │
│   └───bootstrap
│       │   _media.css
│       │
│       ├───mixins
│       │       _border-radius.css
│       │       _screen-reader.css
│       │       _visibility.css
│       │
│       └───utilities
│               _stretched-link.css
│
├───images                  # folder for images
│       ALPSKI.png          # Alpine Skiing icon   
│       bronze.png          # bronze medal logo used on athlete profile pages
│       Canada.png          # Canadian flag used for Tessa and Scott profile pages
│       china.png           # Chinese flag used for Janice profile page
│       favicon.ico         # favicon used at the top of each page
│       FIGSKATE.png        # Figure Skating icon
│       FREESTYSKI.png      # Freestyle skiing icon
│       gold.png            # gold medal logo used on athlete profile pages
│       Himari.png          # Athlete Himari profile photo
│       Himaripic1.jpg      # Himari higlight photo
│       Janice.png          # Athlete Janice profile photo
│       Janicepic1.jpg      # Janice highlight photo
│       Japan.png           # Japanese flag used for Himari profile page
│       Joo Hyuk.png        # Athlete Joo Hyuk profile photo
│       Joo Hyukpic1.jpg    # Joo Hyuk highlight photo
│       logo.png            # Olympic Record app logo     
│       olympic rings.png   # Olympic rings photo used in login
│       Scott.png           # Athlete Scott profile photo
│       Scottpic1.jpg       # Scott highlight photo
│       Shawn.png           # Athlete Shawn profile photo
│       Shawnpic1.jpg       # Shawn highlight photo
│       silver.png          # silver medal logo used on athlete profile pages
│       skiing.png          # Used as icon photo
│       skiing2.jpg         # Used for background on main.html
│       snow.jpg            # Use for background on main.html
│       SNOWBOARD.png       # Snowboard icon
│       snowboarding2.jpg   # Used for background on main.html
│       South Korea.png     # South Korean flag used for Joo Hyuk profile page
│       SPDSKATE.png        # Speed Skating Icon
│       Tessa.png           # Athlete Tessa profile photo
│       tessapic1.jpg       # Tessa highlight photo
│       United States.png   # United States flag used for Shawn profile page
│       welcome1.jpg        #images used on landing page cards
│       welcome2.jpg        # images used on landing page cards
│
├───js
│       bootstrap.min.js
│       jquery.min.js
│       main.js
│       popper.js
│
├───MainPage
│       317284.webp
│       background.jpg
│       scripts.js
│       steep_winter_games_edition-freestyle_skiing-sports_game-boardsport-olympic_games.jpg
│       styles.css
│
├───scripts                     # folder for scripts
│       AlpineSkiing.js         # JS for Alpine Skiing.html
│       athletepage.js          # JS for all individual athlete profile pages
│       athletes.js             # JS for athlete.html
│       authentication.js       # JS for login.html, authenticates users
│       events.js               # JS for events.html
│       eventspage.js           # JS for all individual event information pages 
│       favorites.js            # JS for favourite.html
│       figureskating.js        # JS for Figure Skating.html
│       firebaseAPI_TEAM02.js   # JS contains information used to link to firebase
│       highlight.js            # JS for higlight.html
│       mainpage.js             # JS for main.html
│       skeleton.js             # JS that populates navbar onto each page
│       Snowboarding.js         # JS for Snowboarding.html
│       SpeedSkating.js         # JS for Speed Skating.html
│
├───scss
│   │   style.scss
│   │
│   └───bootstrap
│       │   bootstrap-grid.scss
│       │   bootstrap-reboot.scss
│       │   bootstrap.scss
│       │   _alert.scss
│       │   _badge.scss
│       │   _breadcrumb.scss
│       │   _button-group.scss
│       │   _buttons.scss
│       │   _card.scss
│       │   _carousel.scss
│       │   _close.scss
│       │   _code.scss
│       │   _custom-forms.scss
│       │   _dropdown.scss
│       │   _forms.scss
│       │   _functions.scss
│       │   _grid.scss
│       │   _images.scss
│       │   _input-group.scss
│       │   _jumbotron.scss
│       │   _list-group.scss
│       │   _media.scss
│       │   _mixins.scss
│       │   _modal.scss
│       │   _nav.scss
│       │   _navbar.scss
│       │   _pagination.scss
│       │   _popover.scss
│       │   _print.scss
│       │   _progress.scss
│       │   _reboot.scss
│       │   _root.scss
│       │   _spinners.scss
│       │   _tables.scss
│       │   _toasts.scss
│       │   _tooltip.scss
│       │   _transitions.scss
│       │   _type.scss
│       │   _utilities.scss
│       │   _variables.scss
│       │
│       ├───mixins
│       │       _alert.scss
│       │       _background-variant.scss
│       │       _badge.scss
│       │       _border-radius.scss
│       │       _box-shadow.scss
│       │       _breakpoints.scss
│       │       _buttons.scss
│       │       _caret.scss
│       │       _clearfix.scss
│       │       _deprecate.scss
│       │       _float.scss
│       │       _forms.scss
│       │       _gradients.scss
│       │       _grid-framework.scss
│       │       _grid.scss
│       │       _hover.scss
│       │       _image.scss
│       │       _list-group.scss
│       │       _lists.scss
│       │       _nav-divider.scss
│       │       _pagination.scss
│       │       _reset-text.scss
│       │       _resize.scss
│       │       _screen-reader.scss
│       │       _size.scss
│       │       _table-row.scss
│       │       _text-emphasis.scss
│       │       _text-hide.scss
│       │       _text-truncate.scss
│       │       _transition.scss
│       │       _visibility.scss
│       │
│       ├───utilities
│       │       _align.scss
│       │       _background.scss
│       │       _borders.scss
│       │       _clearfix.scss
│       │       _display.scss
│       │       _embed.scss
│       │       _flex.scss
│       │       _float.scss
│       │       _overflow.scss
│       │       _position.scss
│       │       _screenreaders.scss
│       │       _shadows.scss
│       │       _sizing.scss
│       │       _spacing.scss
│       │       _stretched-link.scss
│       │       _text.scss
│       │       _visibility.scss
│       │
│       └───vendor
│               _rfs.scss
│
├───styles                  # folder for styles
│       athletepage.css     # styles used for all athlete profile pages
│       athletestyle.css    # styles used for athlete.html
│       backtothetop.css
│       eventspage.css      # styles used for 
│       eventstyle.css      # styles used for events.html
│       favorites.css       # styles used for favorites.html
│       highlight.css       # styles used for higlight.html
│       Menustyle.css       # styles used for navbar.html
│
└───text
        nav.html            # navbar for each page

All images were used from unnamed sources on the internet. 
Cannot recall specifically where images were sourced from.

## Contacts
Sahil Rai : - raisahil580@gmail.com

## Acknowledgements
* <a href="https://fontawesome.com/">Font Awesome</a>
* <a href="https://fonts.google.com/">Google Fonts</a>
* <a href="https://getbootstrap.com/">Bootstrap</a>
