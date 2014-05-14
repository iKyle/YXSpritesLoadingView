YXSpritesLoadingView
====================

## OVERVIEW
`YXSpritesLoadingView` is a small library to help you create your custom loader with sprites animation for iOS. We used FBShimmering library to make the loading text slight more insteresting.

![YXSpritesLoadingView](http://yin-xu.com/blog/wp-content/uploads/2014/05/YXSpritesLoadingView_1-e1400096078724.png)
.
![YXSpritesLoadingView](http://yin-xu.com/blog/wp-content/uploads/2014/05/YXSpritesLoadingView_2-e1400096058717.png)


## INSTALLATION
Drag the `YXSpritesLoadingView` folder into your project. `FBShimmering` library is included in `YXSpritesLoadingView` foler, you can remove it if you have that library already. Works for iOS7, using `ARC`

## HOW TO USE

### CUSTOMIZATION
```objective-c
+ (void)show;
+ (void)showWithText:(NSString *)text;
+ (void)showWithText:(NSString *)text andShimmering:(BOOL)shimmering andBlurEffect:(BOOL)blur;
+ (void)dismiss;
```

