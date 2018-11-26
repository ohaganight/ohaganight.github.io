---
permalink: /posts/my-thought-about-pre-compiling-css
---
On the blog I am using the Sass pre compiler which is included in jekyll. A CSS pre compiler is an extention to the ordinary CSS.
It gives you some new feutures to work with. For example you will be able to work with variables, functions (mixins) and nested elements.

I am kind of new to both regular CSS and this preprocessed CSS so it´s hard for me to compare them and give a fare opinion. I have used the variables, which is avaible in ordinary CSS also, in both of them and so far I like how its done in the Sass more. It feels better and you need less code to use them.

I like the way you can organize and structure your CSS with Sass, spliting it up in various files and then get it compiled into just one file, which still is, with todays HTTP-protocol, the fastest way serving it up out there. This might however change in the near future if the new HTTP2-protocol, where mutiple files transfers more efficient, gets standarized.

The possibility of nesting your elements is my favourite feature. It really feels better writing it this way. And it is easier to read. But it's easy to forget this possibility and you will often find yourself writing in the "old" way anyway, which still works as well.

One thing though that goes on the con side is that you have to work with and depend on more software, which might complicate things. Also if you want to debug your code you are in need of other software. But I don't really see the problem in this. And lets say that you want to use a SSG (Jekyll), then you will get the Sass pre compiler as well. And it won't feel much more complex. Then I guess that the features that people really like and use eventually will be implemented as a standard in the regular CSS, and then you won't have this issue. And it's not that complicated, if you know your CSS, using a pre compiler won't be that hard learning.