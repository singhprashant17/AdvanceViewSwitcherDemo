# AdvanceViewSwitcher

An example implementation of AdvanceViewSwitcher.

This library allows adding different views at Runtime, identified by their unique tags, and easy management between switching them.
There is <b>NO LIMIT</b> in number of views that can be added/handled.
Respects all layouts: LinearLayout, RelativeLayout, FrameLayout

<br />
Works seamlessly with both Activity and Fragment.<br />
The demo project has implementation with both Activity and Fragment.

<br />
NOTEABLE METHODS : 

1. <b>public void addMainView()</b> : <br />
   adds the view supplied to the constructor with TAG_MAIN_VIEW

2. <b>public void addViewWithTag(View view, int viewTag)</b> : <br />
   adding the view with specified tag. if tag is already present, returns

3. <b>public void displayViewWithTag(int viewTag)</b> : <br />
   displays view associated with the provided viewTag. If not found, returns

4. <b>public void addAndDisplayWithTag(View view, int viewTag)</b> : <br />
   adds and display the view as soon as after adding

<br /><br />
<b>Screenshots</b><br/>
<br /><br />
<b>View while data is downloading</b><br />
![Alt text](/screenshots/loading.png?raw=true "Loading View")<br /><br />
<b>View when exception occurs</b><br />
![Alt text](/screenshots/exception.png?raw=true "Exception View")<br /><br />
<b>View when success</b><br />
![Alt text](/screenshots/success.png?raw=true "Success View")


<b>Features loved to be added</b>
1. Animation support when switching between views

