# Reading Class 38

1- What are the three criteria an acticity’s intent filter must fulfill in order for a system to send an intent to that activity?

- Action (required)
- Category (optional but often required):
- Data (optional)

2- How does an activity retrieve the Intent that it was started by?

- using getIntent() method.

3- Explain intents to a non-technical friend.

- Think of an Intent like a message or note you want to send to someone. This message contains information about what you want the other person to do or know.

4- Compare and contrast implicit and explicit intents.

- Explicit Intent: Specifically names the component that should handle the intent.
- Implicit Intent: Does not specify the target component; instead, declares an action to be performed, allowing the system to find the best component to handle it.

5- What is the primary information contained within an Intent?

- An Intent in Android is a messaging object that is used for communication between components, the primary information contained within an Intent includes action, data, type, categories and also extras.
