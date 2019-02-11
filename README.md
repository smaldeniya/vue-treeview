# TreeView for Vue.js

## Usage

Install the package into your project:

    npm install --save @ll931217/vue-treeview

or

    yarn add @ll931217/vue-treeview

Add this to your `main.js` file:

```
import Vue from 'vue'
import TreeView from 'vue-treeview'

Vue.use(TreeView)
```

Then add this to where you want to use the treeview:

```
tree-view(:tree="tree")
```

The treeview takes in the prop `tree`, which is in the following structure:

```
[{
  "text": "First Level",
  "nodes": [{
    "text": "Second Level",
    "nodes": [{
      "text": "Third Level",
      "nodes": [{
        "text": "Final Level",
        "value": "The Value"
      }]
    }, {
      "text": "Third Level"
    }, {
      "text": "Third Level",
      "nodes": [{
        "text": "Final Level",
        "value": "The Value"
      }, {
        "text": "Final Level",
        "value": "The Value"
      }]
    }, {
      "text": "Third Level"
    }, {
      "text": "Third Level"
    }, {
      "text": "Third Level",
      "nodes": [{
        "text": "Final Level",
        "value": "The Value"
      }]
    }]
  }, {
    "text": "Second Level",
    "nodes": [{
      "text": "Third Level"
    }, {
      "text": "Third Level"
    }, {
      "text": "Third Level"
    }, {
      "text": "Third Level"
    }, {
      "text": "Third Level"
    }, {
      "text": "Third Level"
    }, {
      "text": "Third Level"
    }]
  }]
}, {
  "text": "First Level",
  "nodes": [{
    "text": "Second Level",
    "nodes": [{
      "text": "Third Level"
    }, {
      "text": "Third Level"
    }, {
      "text": "Third Level"
    }, {
      "text": "Third Level"
    }, {
      "text": "Third Level"
    }, {
      "text": "Third Level"
    }]
  }, {
    "text": "Second Level",
    "nodes": [{
      "text": "Third Level"
    }, {
      "text": "Third Level"
    }, {
      "text": "Third Level"
    }, {
      "text": "Third Level",
      "nodes": [{
        "text": "Final Level",
        "value": "The Value"
      }]
    }, {
      "text": "Third Level"
    }, {
      "text": "Third Level"
    }, {
      "text": "Third Level"
    }]
  }]
}]

```
