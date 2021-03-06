---
title: "Mendix ATS 1.8.0 Release Notes"
space: "ATS (Application Test Suite)"
category: "Release Notes"
---

Date: November 6, 2016

## Supporting AppStore Widgets
Everybody uses widgets from the Mendix App Store in their applications. And of course you want them to be tested like all other parts of your application. Now they can be tested.

We've selected the top widgets from the App Store and added support for testing with ATS.

These are the new widgets now supported by ATS:
* [Dropdown Div Converter](https://appstore.home.mendix.com/link/app/2089/Mendix/DropdownDivConverter)
* [OnChange Inputbox/Textarea](https://appstore.home.mendix.com/link/app/89/Mendix/OnChange-Inputbox)
* [Boolean Slider](https://appstore.home.mendix.com/link/app/1798/Mendix/Boolean-Slider)
* [Simple Checkbox Set Selector](https://appstore.home.mendix.com/link/app/2349/Mendix/Simple-Checkbox-Set-Selector)
* [Checkbox Set Selector](https://appstore.home.mendix.com/link/app/121/Mendix/Checkbox-set-selector-(Table))
* [Grid Selector](https://appstore.home.mendix.com/link/app/266/Mendix/Grid-Selector)
* [Input Reference Selector](https://appstore.home.mendix.com/link/app/99/Mendix/Input-Reference-Selector) (not supported in recording yet)
* [CKEditor](https://appstore.home.mendix.com/link/app/1715/Mendix/CKEditor-For-Mendix) (not supported in recording yet)
* [Bootstrap Wysiwyg Editor](https://appstore.home.mendix.com/link/app/902/Mendix/Bootstrap-Wysiwyg-Editor) (not supported in recording yet)

The [Action Reference Guide](../standard-actions-reference#mendix-appstore-widgets-actions) lists the new actions.

## Action Reference Guide and Tutorial
If you use a widget that is not supported by ATS, you can help yourself and create your own actions. To help you with this, we now provide a [Tutorial](../custom-action-creation-tutorial) that explains how to create an action based on the example of the Boolean Slider widget.

We've also documented all our actions in a [Reference Guide](../standard-actions-reference). It describes all the actions that you can use in your test cases. In addition to that, it also references the internal actions that are very helpful if you want to create your own actions.

## Improved Recording
We've improved the recording functionality to get rid of some unwanted recordings. Previously the recorder would also record a test step when you clicked elements like a table or a dataview. With this release, this does not happen anymore.

## Known Issue
Unfortunately recording for the Input Reference Selector, CKEditor, and Bootstrap Wysiwyg Editor is not possible yet. However, the widgets can still be tested by manually inserting the actions into your test case.
