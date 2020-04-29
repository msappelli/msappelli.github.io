---
layout: post
title:  First Post
date:   2020-04-29 10:00:00
description: experimental post
comments: true
---
I don't really have much to say in this post. Just trying some stuff out

Some math

$$
\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
$$

Some code
{% highlight c++ %}

int main(int argc, char const \*argv[])
{
    string myString;

    cout << "input a string: ";
    getline(cin, myString);
    int length = myString.length();

    char charArray = new char * [length];

    charArray = myString;
    for(int i = 0; i < length; ++i){
        cout << charArray[i] << " ";
    }

    return 0;
}

{% endhighlight %}

<blockquote> Some quote</blockquote>


<div class="img_row">
    <img class="col three" src="{{ site.baseurl }}/assets/img/9.jpg">
</div>
<div class="img_row">
    <img class="col three" src="{{ site.baseurl }}/assets/img/7.jpg">
</div>
<div class="col three caption">
    A simple, elegant caption looks good between image rows, after each row, or doesn't have to be there at all.
</div>
<div class="img_row">
    <img class="col two first" src="{{ site.baseurl }}/assets/img/8.jpg">
    <img class="col one last" src="{{ site.baseurl }}/assets/img/10.jpg">
</div>

Slow-carb four dollar toast Helvetica pop-up. Kale chips next level literally trust fund Pitchfork. Jean shorts Pinterest beard, farm-to-table irony craft beer swag tofu 8-bit Banksy. Quinoa forage fanny pack, pug hashtag Echo Park heirloom Schlitz tote bag artisan Neutra mumblecore 90's shabby chic raw denim.


<div class="img_row">
    <img class="col one first" src="{{ site.baseurl }}/assets/img/11.jpg">
    <img class="col one" src="{{ site.baseurl }}/assets/img/12.jpg">
    <img class="col one last" src="{{ site.baseurl }}/assets/img/7.jpg">
</div>
