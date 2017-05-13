# Verbat-Jithin-MV
Sliding cards


Actually this 'Sliding Cards' consists of  three uiviews placed on a background  uiview in a viewcontroller.

When a user taps on the card it will recognises the gesture and do the further animation action.There are three buttons seen in the view controller.By using this buttons also, we can control the swipe.

  Here buttons are placed above the view.


This Project consists three files.

  1 ViewController
  2 swipeAnimationControl
  3 DraggableView

  ViewController- This is the main view controller.This consists the buttons and this creates background uiview.

  swipeAnimationControl-This is the Uiview that holds the DraggableView.This view will come to above the view controller.

  DraggableView-This is the uiview of  swiping cards.This contains the swipe animation for left and right.

UIPanGestureRecognizer is used to detect the swipe and handle the action when user tries to swipe. By understanding the gesture do the animation type to move the cards.

Initially there is a  ‘card count ‘.
when swiping-limit exceeds ,remove the uivew and shows the next card.
Showing remaining card is based on the checking of remaining card count.

The xcode project is attached this repository.
