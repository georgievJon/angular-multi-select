### v5.5.4
##### Added / Updated
- Possibility to turn off automatic toggling of children/parents.
- CSS cleanup.
- Possibility to use non-default interpolation symbols.
- New API method that allows selection of various items at the same time.

### v5.5.3
##### Added / Updated
- Wrong tag.

### v5.5.2
##### Added / Updated
- Wrong tag.

### v5.5.1
##### Added / Updated
- Wrong tag.

### v5.5.0
##### Added / Updated
- Changed dist directory.

### v5.4.1
##### Added / Updated
- Disable outline on the directive. (CSS)

### v5.4.0
##### Added / Updated
- Major performance improvement by removing the scan/merge parent scopes.
- The item label and button label syntax has changed. Please check docs before upgrading.

### v5.3.21
##### Added / Updated
- Empty selection should trigger an empty string single-output-model.

### v5.3.20
##### Added / Updated
- Wrap API calls inside a 0 $timeout.

### v5.3.19
##### Added / Updated
- Do not uncheck items if they are already checked when using the 'select' API method.

### v5.3.18
##### Added / Updated
- Avoid out of time outputModel replacement.

### v5.3.17
##### Added / Updated
- Wait for DOM ops to finish before starting the directive. (delay-start)
- Better handle wrong values for 'preselect-value'.

### v5.3.16
##### Added / Updated
- Fix a bug when filtering/searching.

### v5.3.15
##### Added / Updated
- Make the single output model mode return a leaf.

### v5.3.14
##### Added / Updated
- Avoid nesting changes inside a $digest.
- Allow to preselect multiple values

### v5.3.13
##### Added / Updated
- Fix a bug with single output model mode.

### v5.3.12
##### Added / Updated
- Make it possible to configure the output model data.

### v5.3.11
##### Added / Updated
- Allow setting a limit to the number of selected items.

### v5.3.10
##### Added / Updated
- Improve performance.

### v5.3.9
##### Added / Updated
- Make it possible to map a single object/value to an output model.

### v5.3.8
##### Added / Updated
- Make it possible to pre-select items via properties.

### v5.3.7
##### Added / Updated
- Scan all $parents when creating labels for the button or for the items.
- Don't copy AngularJS internal values when creating labels.

### v5.3.6
##### Added / Updated
- Don't force the height of the items layer.

### v5.3.5
##### Added / Updated
- Small performance improvements.

### v5.3.4
##### Added / Updated
- Show that none is selected in btn-data.htm template when nothing is selected.

### v5.3.3
##### Added / Updated
- Fix a bug causing the 'setFocus' directive not receiving '$timeout' when minified.
- Now the button label can be styled with any variable from the item itself or from the parent scope.

### v5.3.2
##### Added / Updated
- The directive now exports a simple API that can be used for control purpose.

### v5.3.1
##### Added / Updated
- Fix smart positioning not working quite as expected.

### v5.3.0
##### Added / Updated
- Button icons are part of the CSS now.
- Removed the icons config.

### v5.2.1
##### Added / Updated
- Bring back button customization.
- Now the container layer will be placed on top or on the right of the button if there is no enough space.

### v5.2.0
##### Added / Updated
- Trigger callbacks after applying all the changes (on next tick).
- Show the layer on the left/top of the button if there is no enough space.

### v5.1.5
##### Added / Updated
- Handle destroy event (prevent possible memory leak).

### v5.1.4
##### Added / Updated
- Output model wasn't updated when everything was deselected.

### v5.1.3
##### Added / Updated
- jQuery is still needed for development and testing.

### v5.1.2
##### Added / Updated
- Remove jQuery from the dependencies in package.json.

### v5.1.1
##### Added / Updated
- Performance optimizations (stop $interpolating on each rendered item).

### v5.1.0
##### Added / Updated
- Simplify interpolation process and start using curly braces for it.

### v5.0.9
##### Added / Updated
- jQuery is not required anymore.

### v5.0.8
##### Added / Updated
- Close all other instances of the widget before opening it.

### v5.0.7
##### Added / Updated
- The dropdown is closed after selecting an item if in single mode.

### v5.0.6
##### Added / Updated
- Now it's possible to use vars from the parent scope in the item's label text.

### v5.0.5
##### Added / Updated
- Require grunt-contrib-jasmine >=v0.7.0
- Require jasmine-jquery >= 2.0.0

### v5.0.4
##### Added / Updated
- Require grunt-contrib-uglify >=v0.5.0

### v5.0.3
##### Added / Updated
- Require grunt-contrib-cssmin >=v0.10.0

### v5.0.2
##### Added / Updated
- Fixed a bug with 'Select All' selecting everything while in single mode.
- Implementing support for hidden elements.
- Implement unit tests using Jasmine.

### v5.0.1
##### Added / Updated
- Callbacks have been restored.
- Support dynamic data change of the input data.

### v5.0.0
##### Added / Updated
- Major rewrite of the project.
- The input data format has changed, please read docs.

### v4.0.6
##### Added / Updated
- Ignore more files in the NPM package.

### v4.0.5
##### Added / Updated
- Fixed minified version of JS file.

### v4.0.4
##### Added / Updated
- Add min version of the CSS and the JS files.

### v4.0.3
##### Added / Updated
- Apply some of the PRs from the original project.

### v4.0.2
##### Added / Updated
- Convert spaces to tabs.
- Clean indent style.

### v4.0.1
##### Added / Updated
- I'm forking this project as original project doesn't seem to have any activity.
- Renaming files to something more general.
- Moving from Bower to NPM

### v4.0.0
##### Added / Updated
- You can now customize output-model properties that you need, instead of having all data.
- <a href="https://github.com/isteven/angular-multi-select/issues/201">#201</a> (and other related issues) DOM bug is now fixed.
- <a href="https://github.com/isteven/angular-multi-select/issues/205">#205</a> (and other related issues) CSS bug is now fixed.
- <a href="https://github.com/isteven/angular-multi-select/issues/207">#207</a> (and other related issues) You can now update the directive by modifying the input-model as usual.

##### Deprecated / Breaking Changes
- input-model behaviour is now back like v2.x.x. If you don't re-use your input-model, you should be safe.

### v3.0.0
##### Added / Updated
- Support for AngularJs version 1.3.x (v3.0.0 also supports AngularJs 1.2.x, but beware of the breaking changes).
- Customized text on helper elements.
- 5 new callbacks.
- You can now set minimum characters required to trigger the search functionality.
- You can now define which input-model properties to search from (previously, all input-model properties are searched).
- On close, parent button will now receive focus.
- Using proper semantics (well at least better than previous version).
- Limited support on promise objects.
- Various small optimizations.

##### Deprecated / Breaking Changes
- File name and the directive name have been changed. I am really sorry for this, but this is the only workaround to prevent wrong language statistic in Github (they don''t count files whose name starts with "angular"). The repository name stays the same.
- output-model is now required.
- input-model is now static (not dynamically updated), hence why we need output-model. On the plus side, you now can re-use the input model where necessary.
- default-label is deprecated. Custom text and translations can be done using the translation attribute.

### v2.0.2
##### Added / Updated
- Bring back CSS into bower.json.

### v2.0.1
##### Added / Updated
- <a href="https://github.com/isteven/angular-multi-select/issues/52">#52</a> Form tag is now properly closed.

### v2.0.0
##### Added / Updated
- Unlimited nested grouping. Group headers are clickable to select / deselect all items under the group. Group headers are filter aware, means it will only affect filtered result.
- Helper buttons are now filter aware as well (For example, if you filter something and click 'Select All', the directive will tick all of the filtered result only. Same goes with 'Select None' and 'Reset' ).
- Supports arrow key navigation (up, down, left, right, and spacebar).
- New CSS styling.
- default-label attribute. You can define your default text on the button when nothing is selected.
- on-item-click attribute. This is a callback which will be triggered when a user click an item. Will pass the clicked item to the callback function.
- on-open and on-close callbacks will now pass the multi-select element (HTML) to the callback function.
- max-height attribute. You can define the height of the selection items container.

##### Deprecated / Breaking Changes
- on-focus attribute is deprecated.
- on-blur attribute is deprecated. Use on-close instead, as it will be triggered when user close a directive by clicking outside the directive.
- IE8 will no longer be supported.

### v1.2.0
##### Added / Updated:
- <a href="https://github.com/isteven/angular-multi-select/issues/19">#19</a> Default label on the dropdown button is now configurable using attribute "default-label"="...".
- <a href="https://github.com/isteven/angular-multi-select/issues/16">#16</a> Attribute "max-labels" can now be 0. If set to 0, the dropdown button will only display "(Total: X)".

### v1.1.0
##### Added / Updated:
- Added event callbacks.
- <a href="https://github.com/isteven/angular-multi-select/issues/5">#5</a> Helper elements are now configurable.

### v1.0.0
- First release.
