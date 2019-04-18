
```sequence
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
```

```flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end

st->op->cond
cond(yes)->e
cond(no)->op
```

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>
  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>


## ordered list
>
> 1. Red
> 2. ​    Grren
> 3. ​    Blueee



# Task list

- [ ] a task item
- [x] done  
- [ ] undone



# Math Block


$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$

# markdown

## mark
### down

* Item 1
* Item 2
  * Item 2a
  * Item 2b


1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

As Kanye West said:

> We're living the future so
> the present is our past.

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

#1
mojombo#1
mojombo/github-flavored-markdown#1

~strikethrough~
:smile:

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

```

```