---
layout: page
---

Moby maze screensavers gotta have my pops hoodies lunchables, ok simpson home skillet royal stewart tartan hey arnold bandanas lion king. Mazda mpv independence day ross and rachel bop it. Leopard print bleached hair fila wallet chains michael jordan toyota previa. Vcr big lebowski real world napster adidas cory matthews, da bomb airwalk korn gangsta rap. Flat tops mtv gatorade skidz and zubas ford taurus.

Converse biker shorts fila home improvement snoop dogg. Denim jackets mariah carey bowl cut punk tommy hilfiger jim carrey, yo quiero taco bell good will hunting can’t touch this vcr. Green day mazda mpv pulp fiction business casual scrunched socks, rayon shirts tim “the tool man” taylor adidas doc martens accent braids sideburns. This is your brain on drugs boy bands renting movies at a store hip hop.

**Pellentesque habitant morbi tristique** senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. _Aenean ultricies mi vitae est_. Mauris placerat eleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, `commodo vitae`, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum  rutrum orci, sagittis tempus lacus enim ac dui. [Donec non enim](#) in turpis pulvinar facilisis. Ut felis.

123456789012345678901234567890123456789012345678901234567890123456


## Header Level 2

The admin role gives full privileges to the collaborator, allowing them to manage and publish all content. This role is great for people who are helping build the site, like a developer or designer, since it allows them to upload theme files, change the site’s settings, and invite other collaborators.[^1]

[^1]: This is a footnote!

<code>x</code>
<code>xx</code>
<code>xxx</code>
<code>xxxx</code>
<code>xxxxx</code>

01

1. Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
1. Aliquam tincidunt mauris eu risus.
1. Hoop earrings wearing your cap backwards big lebowski oakleys sitcoms g-shocks.
1. Slacker good will hunting
1. Michael jordan stonewashed blue jeans
1. Meg ryan crimped hair
1. The macarena nike maxin’ velcro sneakers
1. Trl keanu reeves pagers coral paper fortune teller destiny’s child.
1. Denzel washington hush puppies
1. David duchovny digital pets
1. Snoop dogg razor scooter
1. George michael chia pet dream team hottie

> Lorem ipsum this is a blockquote dolor sit amet, consectetur adipiscing elit. Vivamus magna. Cras in mi at felis aliquet congue. Ut a est eget ligula molestie gravida. Curabitur  massa. Donec eleifend, libero at sagittis mollis, tellus est malesuada tellus, at luctus turpis elit sit amet quam. Vivamus pretium ornare est.

### Header Level 3

This role is great for people who are helping build the site, like a developer or designer, since it allows them to upload theme files, change the site’s settings, and invite other collaborators.

- Morbi in sem quis dui placerat ornare. Pellentesque odio nisi, euismod in, pharetra a, ultricies in, diam. Sed arcu. Cras consequat.
- Praesent dapibus, neque id cursus faucibus, tortor neque egestas augue, eu vulputate magna eros eu erat. Aliquam erat volutpat. Nam dui mi, tincidunt quis, accumsan porttitor, facilisis luctus, metus.
- Phasellus ultrices nulla quis nibh. Quisque a lectus. Donec consectetuer ligula vulputate sem tristique cursus. Nam nulla quam, gravida non, commodo a, sodales sit amet, nisi.
- Pellentesque fermentum dolor. Aliquam quam lectus, facilisis auctor, ultrices ut, elementum vulputate, nunc.

![](/uploads/justin-cake.jpg)
{: .fill}

This is the caption.
{: .caption}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus magna. Cras in mi at felis aliquet congue. Ut a est eget ligula molestie gravida. Curabitur  massa. Donec eleifend, libero at sagittis mollis, tellus est malesuada tellus, at luctus turpis elit sit amet quam. Vivamus pretium ornare est.

| # | First name | Last name | Handle |
| --- | -------- | --------- | ------ |
| 1 | Justin | Wang | @justinjaywang |
| 2 | Skylar | Challand | @sskylar |

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus magna. Cras in mi at felis aliquet congue. Ut a est eget ligula molestie gravida. Curabitur  massa. Donec eleifend, libero at sagittis mollis, tellus est malesuada tellus, at luctus turpis elit sit amet quam. Vivamus pretium ornare est.

#### Header Level 4

You can group by any property like date, title, slug, even metadata and taxonomy. Here are a few real-world examples you may want to apply to your theme.

```css
#header h1 a {
  display: block;
  width: 300px;
  height: 80px;
}
```

##### Header Level 5

For the last week publishing in the Siteleaf interface has been powered by our API. This has been a requested feature by some of our users and ourselves. Its behavior is bit different than some of our other API endpoints, so let’s go over it.

###### Header Level 6

**Pellentesque habitant morbi tristique** senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. _Aenean ultricies mi vitae est_. Mauris placerat eleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, `commodo vitae`, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum  rutrum orci, sagittis tempus lacus enim ac dui. [Donec non enim](#) in turpis pulvinar facilisis. Ut felis.

---

### Archive page

Grouping posts by year is a common pattern on archive pages. Since Siteleaf already <a href="/help/themes/naming-your-files/">generates archive pages</a> for us, we can easily sprinkle in <code>group_by</code> and have a beautiful blog archive in minutes.

First, let’s group our posts by year:

{% highlight liquid %}{% raw %}{% assign posts_by_year = posts | group_by:"year" %}{% endraw %}{% endhighlight %}

<small>Note: We are using <code>posts</code> in this case rather than <code>site.posts</code> because we only want posts relative to this page (but either could work).</small>

Now we can display our grouped posts:

```liquid
{% raw %}{% for year in posts_by_year %}
  <h2>{{year.name}}</h2>
  <ul>
  {% for post in year.items %}
    <li><a href="{{post.url}}">{{post.title}}</a></li>
  {% endfor %}
  </ul>
{% endfor %}{% endraw %}
```

**Extra credit:** We could take this a step further and do a multi-level group, showing posts by year AND month.

In case you&rsquo;re wondering, `%B` gives us the month name (e.g. “April”) from a date. For full documentation see our <a href="/help/themes/filters-and-tags/date-formating">date formatting</a> guide.

Until next time, happy coding!
