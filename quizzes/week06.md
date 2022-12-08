# Single Page Applications with Vue

**1.** What is the entrypoint of an application?

```
The javascript file that the browser loads first, that js file then calls everything else it needs
```

**2.** What is the difference between a vue `component` and `page`?

```
Very little technically, but a page generally has a route attached to it, and components get loaded into pages
```

**3.** What feature of Vue can be used to repeat an element using a collection of data?

```
v-for
```

**4.** What are the three tags that make up a Vue component?

```
<Script> <template> <Style>
```

**5.** What does the `L` represent in the `SOLID` principles?

```
Liskov substitution principle, essentially it boils down to that a class that extends the parent should be able to be used instead of the parent
```

**6.** Which component in Vue does the vue-router use to mount pages onto?

```
<slot>
```

**7.** What is the difference between the `AppState` and the state object within a component?

```
AppState can be access globally, but the state within a component can only be accessed outside if you bind to it
```

**9.** What is the responsibility of `Services` in our Vue projects?

```
Services contain functions that deal with appstate data
```

**10.** Which file contains the root element of your Vue project?

```
/src/app.vue
```

**11.** The **\_\_** tag is used to alter the styling of your entire Vue project. Adding the **\_\_** attribute to this tag will limit it to just the component it exists. Fill in the blank.

```
gobal, scoped
```

**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?

```
ref()
or computed(()=>varHere)
```
