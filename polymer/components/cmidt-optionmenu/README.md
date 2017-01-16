# cmidt-option-menu
Polymer Option Menu like Android option menu. Option Menu automatically put the item into overflow menu when there is no room available.

# Install the Option Menu

1. Make sure bower is installed.
2. Run the following command: bower install https://github.com/cmidt-veasna/cmidt-optionmenu.git --save

# Define Option menu

```html
<cmidt-option-menu id="option">
    <cmidt-option-menu-item id="shopping" title="add shopping" icon="icons:add-shopping-cart"></cmidt-option-menu-item>
    <cmidt-option-menu-item id="create" title="create" icon="icons:create" disabled></cmidt-option-menu-item>
    <cmidt-option-menu-switchable-item id="switchable0" auto>
        <cmidt-option-menu-item id="download" title="download" icon="icons:cloud-download" selected></cmidt-option-menu-item>
        <cmidt-option-menu-item id="past" title="paste" icon="icons:content-paste"></cmidt-option-menu-item>
    </cmidt-option-menu-switchable-item>
    <cmidt-option-menu-item id="copy" title="copy" icon="icons:content-copy" alway-hide></cmidt-option-menu-item>
    <cmidt-option-menu-item id="attachment" title="attachement" icon="icons:attachment" alway-hide></cmidt-option-menu-item>
    <cmidt-option-menu-item id="fingerprint" title="fingerprint" icon="icons:fingerprint" alway-hide></cmidt-option-menu-item>
</cmidt-option-menu>
```

For more information visit https://cmidt-veasna.github.io/polymer/polymer/components/cmidt-optionmenu

# Running Tests

```
$ polymer test
```

Option Menu is already define certain test scenario however it does not cover all the case. We will Update it in the future. To test
Option Menu run `polymer test` to under Cmidt Option Menu.
