# Create-simple-shopping-app-interface-Task
TaskFadeAnimation is a class that extends PageRouteBuilder to be used as an animation while navigation.
class takes 2 parameters : 
  - screen (Widget) : -required- the screen wanted to be pushed in the navigation stalk : -optional- the duration of the animation.
  - animationDuration (Duration) :

To use that class (exammple):
"""Navigator.push(
              context,
              TaskFadeAnimation(
                screen: const HomeScreen(),
                animationDuration: const Duration(seconds: 2)
              )
            );"""
