## CODECADEMY course for VUE.JS

#### Directives (perform complex front end tasks)

```
v-model="username" // automatically binds form fields to dynamic values in data: {} on the Vue app
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
</form>
```

---

#### Data (dynamic data)

---

#### Methods

---

#### Computed

---

#### Watch
