#### XYZ Reader - Project 5, Android Nanodegree Course, Udacity
This application show a list of articles fetched from internet. All titles, cover images, and information come from there.

This project has been modified to implement material design as per the project requirement of P5 "Make Your App Material" under Udacity Android Nanodegree program.

Main focus was on usage of CoordinatorLayout, AppBarLayout, CollapsingToolbarLayout to manipulate toolbar, scrolling and parallax. Shared Transition, Enter/Exit transitions were also implemented.

Few things I learnt/ implemented in this project:

* Added Color theme
* Adjusted positioning of logo
* Changed stickybroadcast to localbroadcastmanager
* Implemented swiperefreshcode listener
* Added to show toast when no internet connection
* Added empty view to recycle view
* Added About activity
* Added coordinatorlayout/appbarlayout
* Added animation to main image logo in toolbar
* Added CoordinatorLayout to detail activity
* Replaced custom scrollview with NestedScrollView
* Removed MaxWidthLinearLayout and few other classes
* Improved the ImageLoaderHelper class
* Added singleTop mode to main activity
* Added shared transition for title from main to detail
* Added slideup/down on enter/exit transition of detail activity
* Added fixed page width for w800dp size and other optimizations for multiple screens
* Use of merge tag in layout
* Added swipe hint