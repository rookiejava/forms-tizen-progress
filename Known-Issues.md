# Known Issues

Due to the inherent nature of Tizen, the Tizen backend contains a few limitations on the Xamarin.Forms APIs - these limitations are to be eliminated in future releases.
The following classes are not supported:
 - AppLinkEntry
 - OpenGLView

A full list of limitations across devices is available at [here](https://developer.tizen.org/development/api-reference/.net-application/current-xamarin.forms-limitations).

Use **[GitHub issues](https://github.com/rookiejava/forms-tizen-progress/issues)** to report new bugs. See [FAQ](https://github.com/rookiejava/forms-tizen-progress/faq) for solutions to common issues.

## Samsung Smart TV
| Class             | Type     | Name      | Remarks | Result when the feature is used |
|-------------------|----------|-----------|---------|---------------------------------|
| ActivityIndicator | Property | IsRunning |         | The `IsRunning` state is not updated when `IsEnabled` is set to `false` and back to `true` again. |
| Button            | Property | Image     |         | When the `Button` gets the focus, the image area becomes black. |
| DatePicker        | Class    |           |         | The date text is not shown on the picker dialog. |
| Entry             | Class    |           |         | It is vague if the `Entry` has the focus. |
|                   |          |           |         | The virtual keyboard does not hide when `Done`, `Cancel`, or `Back` key is pressed. |
| Editor            | Class    |           |         | It is vague if the `Editor` has the focus. |
|                   |          |           |         | The virtual keyboard does not hide when `Done`, `Cancel`, or `Back` key is pressed. |
| FrameLayout       | Property | Padding   |         | The `Padding` value is not applied dynamically. |
| Image             | Class    |           |         | The image source which is over 4Mb is not shown on the screen due to the TV policy. |
| Keyboard          | Class    |           |         | The keyboard type is not various. |
| SearchBar         | Class    |           |         | The clear, `X`, button in the search bar is not shown. |
| TextCell          | Property | Detail    |         | The `Detail` text is not shown by the UX policy. |
|                   |          | IsEnabled |         | When the `TextCell.IsEnabled` is set to `false`, text in the Cell is dimly visible . |
| TimePicker        | Class    |           |         | The time text is not shown on the picker dialog. |
| WebView           | Class    |           |         | The Application crashes when the `WebView` is used.|
