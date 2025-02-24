title: Drag and drop canvas shapes with Svelte
layout: svelte_page

---

To enable drag&drop for any node on canvas you just need to pass `draggable: true` property into the component's config prop.

svelte-konva automatically keeps your config in sync with the Konva node on `dragend`. See the [bindings](/docs/svelte/Bindings.html) doc page for more details.

<iframe src="https://codesandbox.io/embed/github/konvajs/site/tree/master/svelte-demos/drag_and_drop?hidenavigation=1&view=split&fontsize=10&module=/App.svelte" style="width:100%; height:500px; border:0; border-radius: 4px; overflow:hidden;" sandbox="allow-modals allow-forms allow-popups allow-scripts allow-same-origin"></iframe>
