# network-status-detection

a web component helps you detect network status easily

## Use with Polymer (Or any databinding System)

```html
<network-status-detection
  isOnline="{{isOnline}}"></network-status-detection>


<template is="dom-if" if="[[!isOnline]]">
  <!-- anything inside will show only when offline  -->
  <div class="offline_reminder">U r offline</div>
</template>
```
