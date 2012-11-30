mywiki
======

Technical notes

GestureRecognizer - easier than touches as there is no need to determine different type of touches manually.
http://www.raywenderlich.com/2343/how-to-drag-and-drop-sprites-with-cocos2d

CCTouchDispatcher - unlike gestures, can be automatically propagated through layers.
(handling touch through multiple layers)
http://stackoverflow.com/questions/5222375/cocos2d-handling-touch-with-multiple-layers


To propogate gestures through layers, let the scene handle the gestures and then manually detect which layer should receive the gesture and then ask the layer to handle the gesture.
(handling gestures through multiple layers)
http://www.cocos2d-iphone.org/forum/topic/16001

Sharing data across apps - iCloud is one option but requires to be online?

http://landonf.bikemonkey.org/code/iphone/iPhone_Framework_Support.20081202.html

Useful library:
https://github.com/AFNetworking/AFNetworking

