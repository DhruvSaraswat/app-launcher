# app-launcher
I wanted to launch all my everyday applications at a keystroke. Hence this was born. Necessity, as they say, <i>is</i> the mother of invention.

## Getting Started
Simply clone the project, navigate to the directory where ```launch_applications.applescript``` is located, and then run the command from Terminal -

```AppleScript
osascript launch_applications.applescript
```

## Assign a Keyboard ShortCut to this AppleScript

If you wish to run this AppleScript at the hit of a keystroke -

<ol>
  <li><a href="https://www.addictivetips.com/mac-os/convert-an-applescript-to-an-app-on-macos/">Save launch_applications.applescript as an application.</a></li>
  <li>Open Automator on your MacOS.</li>
  <li>Select Quick Action.</li>
  <li>Select "no input" from the "Workflow receives" drop-down list.</li>
  <li>Select "Launch Application" from the list of Actions and drag it to the right hand side.</li>
  <li>Select the application which you saved at step 1.</li>
  <li>Save the Automator file.</li>
  <li>Go to System Preferences -> Security & Privacy -> Privacy tab -> Select Accessibility and add Automator to the list of apps which can control your computer.</li>
  <li>Go to System Preferences -> Keyboard -> Shortcuts -> Services. You should see the Automator file you saved at step 7 listed. Select it.</li>
  <li>Double click on "Add Shortcut" and press the shortcut keys you wish to assign to the applescript. <b>Take care not to assign a shortcut already assigned to some other action on MacOS !</b></li>
</ol>

Voila ! Click the KeyBoard shortcut from any window and watch the magic happen.
