The rapidoc exposes only the before-render hook to modify the spec before it renders.
After that , there is no method to modify spec.

In this custom build, I added two methods

1. getResovledSpec()
2. triggerRender()

getResovledSpec() is a getter , and it gives the spec object which can be mutated
triggerRender simply triggers a render of Lit

---

Here in _Update an existing pet_ example, the php sample code is present in yaml.
I just added a JS snippet at runtime and trigger a render.
