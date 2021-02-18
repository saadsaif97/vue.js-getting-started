## CODECADEMY course for VUE.JS

#### Directives (perform complex front end tasks)

```
v-model="username" // automatically binds form fields to dynamic values in data: {} on the Vue app
v-bind:disabled="!formIsValid" // v:bind binds the attribute to an element based on condition or a component prop to an element
v-bind:class="{ active: isActive }" // binds the class to element based on condition
v-on:submit="handleSubmit" // vue handle the events by v-on directive handle submit is from methods: {}
SHORTHAND FOR EVENT HANDLERS IS @
@submit/@reset
```

On pressing reset button; form rests but data does not, so we have to clear it manually by method
@reset="resetFields" // resetFields is from the methods: {}

###### Event modifiers:

- @submit.prevent // event.preventDefault()
- @submit.stop // event.stopPropagation()

```
<form @reset="resetFields"  @submit.prevent="submitForm">
   ...
   <button type="reset" class="reset">Reset</button>
   <button type="submit" v-bind:disabled="!formIsValid">Confirm Tickets</button>
</form>
```

###### Input modifiers:

Vue offers the following three modifiers for v-model:

- .number — automatically converts the value in the form field to a number
- .trim — removes whitespace from the beginning and ends of the form field value
- .lazy — only updates data values when change events are triggered (often when a user moves away from the form field rather than after every keystroke)

---

#### Data (dynamic data)

---

#### Methods

---

#### Computed

---

#### Watch
