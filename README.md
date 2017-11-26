
# vue-semantic-ui-checkbox
Semantic UI Checkbox built using Vue js for those who dont want to user jQuery in thier project but want all the functionality provided by jQuery. This project contains only semantic ui checkbox component i will create other components in separate projects

# How to use it

#install
npm install vue-semantic-ui-checkbox --save

#import
#simple checkbox
import {VueSemanticUiCheckbox} from 'vue-semantic-ui-checkbox'
```html
<div class="ui padded segment">
  <h4 class="ui header">Checkbox</h4>
  <vue-semantic-ui-checkbox label="Make my profile visible" name="simple"></vue-semantic-ui-checkbox>
</div>
```

#group checkbox
import {VueSemanticUiCheckbox} from 'vue-semantic-ui-checkbox'
```html
<div class="ui padded segment">
  <h4 class="ui header">Group</h4>
  <vue-semantic-ui-checkbox-group>
    <vue-semantic-ui-checkbox 
      slot="parent" 
      name="fruits" 
      class="master" 
      label="Fruits"
    ></vue-semantic-ui-checkbox>
    <div class="list" slot="children">
      <div class="item">
        <vue-semantic-ui-checkbox 
          name="apple" 
          class="child" 
          label="Apple"
        ></vue-semantic-ui-checkbox>
      </div>
    </div>
  </vue-semantic-ui-checkbox-group>
</div>
```
for all examples please visit: https://github.com/jaskaran-kalra/vue-semantic-ui-checkbox/blob/master/src/views/Checkbox.vue

