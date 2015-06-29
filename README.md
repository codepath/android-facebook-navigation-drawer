# android-facebook-navigation-drawer
The new material design style navigation drawer

## Overview

The navigation drawer is a panel that displays the app’s main navigation options on the left edge of the screen.
The objective of this exercise is to build navigation drawer based on material design guidelines. 

To achieve this, there are a few different components in this app:

1. `DrawerLayout` - The main layout for your activity. This will contain a FrameLayout which displays the contents of the fragment selected
2. `NavigationView` - It is a container for the Header View and Menu which you are going to use in your sliding drawer
3. `drawer_view` - This will be the list of items you show in the Drawer. Items can be grouped into sub-groups also using this menu xml file
4. `ActionBarDrawerToggle` - This is the class used to indicate to the user when a drawer is being opened or closed

## Usage
This app is intended to be the base project on top of which new features can be added. To use it, clone the project and import it using the following steps:

![Imgur](http://i.imgur.com/x5iXb8Y.gif)

Once you have imported base app, go ahead and run it, and you should see the following output : 
  
![Imgur](http://i.imgur.com/ju5Mprkm.png)

Now we will go ahead and implement the exercise. At the end of exercise, final output will be 

![Imgur](http://i.imgur.com/XoBgJBVm.gif)
