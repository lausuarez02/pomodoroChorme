# pomodoroChorme


In order to create a Google Chrome Extension you have to create the following files so google can understand it

![GitHub Logo](/first.jpeg)

Once you have this files inside of the manifest.json You have to do the following

{
    "manifest_version" : 2,
    "name": "Pomodoro Timer",                       //Here you put the name of your project
    "description": "Timer for productivity",        //The description that you want to give to it
    "version":"1.0.0",                              //The version    
    "icons": {"128": "icons8-hourglass-90.png"},    //The icon should be of a max of 128px for 128px
    "browser_action": {
        "default_icon": "icons8-hourglass-90.png",
        "default_popup":"popup.html"                //Here the popup.html which will be the file that Google will read
    },
    "permissions":["activeTab"]
}

![manifest](/second.jpeg)


