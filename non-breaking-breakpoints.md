# Setting Non-Breaking Breakpoints

In this section of the workshop we're going to take a look at how you can use Rookout to set a **Non-Breaking Breakpoint** within the To-Do app source code.  Setting **Non-Breaking Breakpoints** is similar to how you would set a breakpoint in your IDE but in this case, the application never stops its execution.  They allow Rookout to capture a snapshot of the underlying state of the application including local variable values, meta data, and a stack trace leading up to where the snapshot was captured.  The great thing is that this can be done in any environment where the application is running (including Staging and Producation) with very minimal performance overhead (about the same as if you were writing log lines yourself within the code).

This section of the workshop will guide you through the following areas:

* Setting a **Non-Breaking Breakpoint** within the To-Do app source code
* Interacting with the To-Do app to trigger the code where the **Non-Breaking Breakpoint** is set
* Reviewing the snapshot data that Rookout collects

Let's get started:

1. From the **Source View** panel on the left side of the screen, expand the source code repository files and click on *app.py* to open it in the **source view panel**.

<p><img src="images/bp-source-view.png" width="800"/><p>

2. Let's set a **Non-Breaking Breapoint** that will trigger and collect a snapshot every time we add a new to-do item to our list.  In order to do that, we'll need to find the **add_todo()** method.  The **add_todo()** method starts on line 88.  Let's set a **Non-Breaking Breapoint** on the last line of the function at line     