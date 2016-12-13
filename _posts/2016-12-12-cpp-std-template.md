---
layout: post
title:  "Standard Template Library"
date:   2016-12-12 22:01:43 +0530
categories: "template <class T>>"
permalink: /_posts/
---
post-002

This is the way of the future. A method to create web pages minus all the gunk that conventional
CMS offers. The single static web page view. Dynamic and fast:

I plan on going through the STD library writing short programs with the most used 
methods.

My original plan was to create a ~Desktop/programmming/cpp/c++11/ directory 
and start with folders describing what we plan on teaching. 

We will start describing the template class due to the fact that it's such
a fundamental core component for multiple uses.

When required I will post the complete code so you can compile it quickly.
The output() function can accept most any fundamental data type and outputs
to standard output <iostream>

{% highlight c++ %}
#include <iostream>
using namespace std;

template <class T>
void output (const T & n)
{
  cout << n << endl;
}

int main() {
   output(500);
   output(3.14159);
   output("This is a long string");
   return 0;
}

{% endhighlight %}



Notice the multiple ways you can output using the template class.



