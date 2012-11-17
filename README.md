mywiki
======

Technical notes

GestureRecognizer - easier than touches as there is no need to determine different type of touches manually.
http://www.raywenderlich.com/2343/how-to-drag-and-drop-sprites-with-cocos2d

CCTouchDispatcher - unlike gestures, can be automatically propagated through layers.

To propogate gestures through layers, let the scene handle the gestures and then manually detect which layer should receive the gesture and then ask the layer to handle the gesture.
