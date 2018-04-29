---
title:  "Loop through Forestry blocks with Jekyll?"
answers:
- text: "Donec sed odio dui. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Sed posuere consectetur est at lobortis. Maecenas faucibus mollis interdum."
  user: "Dan theMan"
  votes: 2
  replies:
  - text: "Donec sed odio dui. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Sed posuere consectetur est at lobortis. Maecenas faucibus mollis interdum."
    user: "Laura Bora"
    votes: 0
- text: "Sed posuere consectetur est at lobortis. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas faucibus mollis interdum. Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus."
  user: "Scott Gallant"
  votes: 1
votes: 23
---
Donec sed odio dui. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Sed posuere consectetur est at lobortis. Maecenas faucibus mollis interdum.

```
<h2>{{ .Title }}</h2>
<p>{{ .Content }}</p>
<hr>
<div class="responses">
  {{ .Params.response }}
</div>
```
Donec sed odio dui. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Sed posuere consectetur est at lobortis. Maecenas faucibus mollis interdum.
