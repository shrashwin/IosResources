#### This is the list of helpful libraries that I use in my app frequently and most of the apps.

### [Alamofire](https://github.com/Alamofire/Alamofire)
    Alamofire is an HTTP networking library written in Swift.

### [ObjectMapper](https://github.com/tristanhimmelman/ObjectMapper)
    ObjectMapper is a framework written in Swift that makes it easy for you to convert your model objects (classes and structs) to and from JSON.

    Usage: I usually use Alamofire and ObjectMapper together ie. use Alamofire for api call and then pass the response json to my modal class which confirms to ObjectMapper's Mappable protocol

### [SDWebImage](https://github.com/SDWebImage/SDWebImage)
    This library provides an async image downloader with cache support. For convenience, we added categories for UI elements like UIImageView, UIButton, MKAnnotationView.

    Usages: When we want to load images to uiimage, uibutton, and mkannotationview.

### [SVPullToRefresh](https://github.com/samvermette/SVPullToRefresh)
    These UIScrollView categories makes it super easy to add pull-to-refresh and infinite scrolling functionalities to any UIScrollView (or any of its subclass).

    Usage: There are cases when we want to load data from server in pages i.e infinite scrolling or cases when we want to pull table or scrollview to refresh the data or refetch the data from server starting at page 0

### [MBProgressHUD](MBProgressHUD)
    MBProgressHUD is an iOS drop-in class that displays a translucent HUD with an indicator and/or labels while work is being done in a background thread. The HUD is meant as a replacement for the undocumented, private UIKit UIProgressHUD with some additional features.

    Usage: Cases when we want are fetching data from the server and show the information to user as well as stop the view interaction.

### [RangeSeekSlider](https://github.com/WorldDownTown/RangeSeekSlider)
    RangeSeekSlider provides a customizable range slider like a UISlider. This library is based on TomThorpe/TTRangeSlider (Objective-C) and made with Swift.

    Usages: As the name suggest itself, this is my go to library when I need slider with more than one slide touch functionality i.e. slider in range.

### [MGSwipeTableCell](https://github.com/MortimerGoro/MGSwipeTableCell)
    MGSwipeTableCell is an easy to use UITableViewCell subclass that allows to display swipeable buttons with a variety of transitions.This library is compatible with all the different ways to create a UITableViewCell: system predefined styles, programmatically created cells, cells loaded from a xib and prototype cells within a storyboard.

    Usage: This is my go to library when I need to implement cell slide for more functionalities like delete, archive, and other functionalities. Classic example for this will be gmail app where we can slide to reveal more options in each email thread.

### [CountryPickerSwift](https://github.com/4taras4/CountryCode)
    Make your UIPickerView a class of CountryPicker, set its countryPickerDelegate and implement its countryPhoneCodePicker method.

    Usages: I tend to use this library when I need to pick countries for information update. Yes we can do it ourselves and not use this library but why not? This has array of all the countries, is highly customizable and also images for flag for each country which are optimized for low space usage.

### [GooglePlacePicker](https://github.com/googlemaps/maps-sdk-for-ios-samples)
    Usage: With this library, we do not need to make our own view controller to fetch the geolocation. This library usage totally depend upon the client requirement. If client has no obligations put for its usage i.e. no need to have our own design, this is go to library for location picking. This gives us the co-ordinates and all other details for the place. 
