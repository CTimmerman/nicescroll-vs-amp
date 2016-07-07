# nicescroll-vs-amp
Test case that shows Azure media player failure when jquery.nicescroll plugin is initialized.

Complete log of IE11:
```
DOM7011: The code on this page disabled back and forward caching. For more information, see: http://go.microsoft.com/fwlink/?LinkID=291337
test.html
HTML1300: Navigation occurred.
test.html
SEC7123: Request header content was not present in the Access-Control-Allow-Headers list.
videotag_playready_token.html
SCRIPT7002: XMLHttpRequest: Network Error 0x80070005, Access is denied.

videotag_playready_token.html
[11:27:10.048] error: azureHtml5JS: common: XHR failed status:  (0), readyState: 4
[11:27:10.055] error: videojs: (CODE:542113798 undefined) Http: 0x00200000 [object Object]
```
