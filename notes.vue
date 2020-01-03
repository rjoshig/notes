vue-cli installed globally

vue --version

vue create hello-world

v-if="condition"
"Directives are prefixed with v-

"test"


event modifieers:
    v-on:mousemove.stop=
key modifiers
    v-on:keyup.enter
2-way binding
    v-model

el
data:
computed:
methods: 
watch: This is most useful when you want to perform asynchronous or expensive operations in response to changing data.


sudo apt install compiz compizconfig-settings-manager compiz-plugins-extra


Ctrl + Enter


data ----- > state

methods ----- > actions

computed ----- > getters

m ----- > mutation (used to commit/track changes)

actions
mutations always synchrnous
state
getters --- like methods


access store by dispatching from components



Application-level state is centralized in the store.

The only way to mutate the state is by committing mutations, which are synchronous transactions.

Asynchronous logic should be encapsulated in, and can be composed with actions.

https://vuex.vuejs.org/guide/structure.html


Components name:
  Single Component:      PascalCase.vue
  Base Co mnponent: Base App or V