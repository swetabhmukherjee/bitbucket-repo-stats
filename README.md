# bitbucket-repo-stats
Smashing widget to display a Bitbucket Repository Statistics


# Description
Widget for [Smashing](http://smashing.github.io/) that shows the Bitbucket Repository Stats. 

# Usage
To use this widget, copy contents of `widget` folder into your `widget` directory, and copy the contents of `jobs` folder into  your `/jobs` folder.

To include the widget in a dashboard, add the following snippet to the dashboard layout file:
```html
<li data-row="1" data-col="1" data-sizex="1" data-sizey="1">
      <div data-id="welcome" data-view="Text" data-title="Stats for 'firebase_example' Repo on BitBucket:" style="background-color:maroon"></div>
    </li>
  <li data-row="2" data-col="1" data-sizex="1" data-sizey="1">
    <div data-id="branches_count" data-view="branches_count" style="background-color:maroon"></div>
  </li>
 <li data-row="3" data-col="1" data-sizex="1" data-sizey="1">
    <div data-id="pullrequests_count" data-view="pullrequests_count" style="background-color:maroon"></div>
  </li>
  <li data-row="4" data-col="1" data-sizex="1" data-sizey="1">
    <div data-id="issues_count" data-view="issues_count" style="background-color:maroon"></div>
  </li>
```
