### Posts

<ul class="postsList">
  {% for post in site.posts %}
    <li class="postsList__item">
      <a class="postsList__link" href="{{ post.url }}">{{ post.title }}</a> <div class="postsList__date">({{ post.date | date: site.day_format }})</div>
    </li>
  {% endfor %}
</ul>
<!---
### Tags

<ul>
{% for tag in site.tags %}
  <li><a href="">{{ tag[0] }}</a></li>
{% endfor %}
</ul>
--->

### Bio

Hi, my name is Nicolai Sandow, born in 1977 in Berlin. I've worked as a frontend webdeveloper since 2002, mainly for local news publishers ([Medienhaus Lensing](https://www.lensingmedia.de/) in Dortmund, [DuMont](https://www.dumont.de/) in Cologne). My professional skills include state-of-the-art HTML and CSS, [frameworkless](http://frameworklessmovement.org/) Javascript, excellent bitmap and vector editing, Git, Scrum and a focus on usability and SEO.

As a hobby I've been running a [gaming community](https://www.systemshock.org) since 2005 about the [System Shock](https://en.wikipedia.org/wiki/System_Shock_2) games series.
I like reading <s>Jane Austen</s> stories about British Explorer [Percy Fawcett](https://en.wikipedia.org/wiki/Percy_Fawcett) to my wife, helping people, growing palm trees, and a cold beer. As I discovered, I have strongly held opinions about web standards, net neutrality, and the value of voluntary work.
Here's a silly [picture of me](/img/nicolai.jpg).

### Contact
<form action="https://formspree.io/f/mqkgbajv" method="POST">
  <input type="text" name="_replyto" placeholder="Your email">
  <textarea name="message" placeholder="Your message" style="width:500px;height:200px;"></textarea>
  <button type="submit">Send</button>
</form>

### Links

- [schwarzsilber.de (2004-2015)](http://www.schwarzsilber.de/swsi2015/)
- [schwarzsilber.de (2001-2003)](http://www.schwarzsilber.de/swsi2015/#%5B%5BThe%20first%20layout%20of%20this%20site%5D%5D)
- [https://www.systemshock.org](https://www.systemshock.org)
- [https://codepen.io/kolya](https://codepen.io/kolya)
- [https://stackoverflow.com/users/1225787/kolya](https://stackoverflow.com/users/1225787/kolya)


<!---
You can use the [editor on GitHub](https://github.com/KolyaKorruptis/.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

- https://devhints.io/jekyll
- https://jekyllrb.com/docs/variables/
- https://jekyllrb.com/docs/posts/

### Markdown

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.



--->
