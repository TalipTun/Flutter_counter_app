# Flutter_counter_app

A simple Flutter counter application where you can increment or decrement. Here is what I learned from this project: 

StatefulWidget vs. StatelessWidget: You solidified your understanding of StatefulWidget and its associated State class. You know that if a part of your UI needs to change based on user interaction or data, it needs to be a StatefulWidget.

setState() for UI Updates: You've mastered the core mechanism for updating the UI in Flutter. You understand that changing a state variable (like _counter) alone isn't enough; setState() is necessary to tell the framework to rebuild the widget and reflect the new value.

Event Handling with Multiple Actions: You've gone beyond a single action and implemented two distinct actions (_incrementCounter and _decrementCounter) tied to different buttons, demonstrating how to manage multiple user interactions.

Layout with Row: You learned how to arrange multiple widgets horizontally using the Row widget, specifically to place both FloatingActionButtons side-by-side. This builds on your understanding of Column and Center for vertical and central alignment.

Spacing with SizedBox: You used SizedBox to add explicit spacing between your two FloatingActionButtons, which is a common and effective way to control layout aesthetics in Flutter.

Reusability of Widgets: You saw how you could reuse the FloatingActionButton widget, just changing its onPressed callback, tooltip, and child to achieve different functionalities.
