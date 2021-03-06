# parenting - the Python way <img src="https://github.com/till-io/parenting/blob/main/resources/logo.png" width=170 align="right" />

[![Version](https://img.shields.io/pypi/v/parenting.svg)](https://pypi.org/project/parenting/)
[![License](https://img.shields.io/pypi/l/parenting.svg)](https://raw.githubusercontent.com/till-io/parenting/master/LICENSE)
[![Status](https://img.shields.io/badge/status-stable-green.svg?maxAge=3600)](https://pypi.org/project/parenting/)

***
<center>
<i>Never lend your car to anyone to whom you have given birth.</i> <br>
- Erma Bombeck
</center>

***

I have just recently become a first time dad and this is the greatest joy of my life. There is so much to learn and yet my software development experience has prepared so little for this. After my first weeks of daddying, I put some of my learnings into a - what else could I do - Python library. Obviously, this is not going to solve your problems, but maybe it can humor you a bit and this is what dad humor is for.

## Usage

<code>parenting</code> is published on <a href="https://pypi.org/project/parenting/">PyPi</a> and you can get it with the standard <code>pip</code> interface. <code>parenting</code> needs Python 3.6 and uses <a href="https://pypi.org/project/wasabi/"><code>wasabi</code></a> as a pretty printer.

Once you downloaded the library, you find a standard python interface. I implemented classes depending on your relationship to the baby. They yield mostly the same results, however, parenting is not just the parents job sometimes and it is important to recognize that. I currently implemented ten classes so far: <code>mommy()</code>, <code>daddy()</code>, <code>partner</code>, <code>auntie()</code>, <code>uncle()</code>, <code>sister()</code>, <code>brother()</code>, <code>grandma()</code>, <code>grandpa()</code>, <code>friend()</code>.

    # import the class you need, for me its daddy
    from parenting import daddy

    # init the class
    dad = daddy()

Ones the class is initiated, you get access to the <code>get_advice()</code> method. This will guide you through a dialog, in which we try to find your baby's problem together. I must admit, this is obviously simplified, yet inspired by ``So beruhige ich mein Baby`` an amazing book by <a href="https://www.verlagsgruppe-patmos.de/autor/christine-rankl-1968">Christine Rankl</a>. 

<p align="center">
  <img src="https://github.com/till-io/parenting/blob/main/resources/parenting.png" width="400">
</p>

The <code>get_advice()</code> method implements a bunch of criteria to check when your baby starts complaining. In the first three months, complaining is typically screaming rather than actively communicating what the exact problem is.

Anyway, I hope this helps you. Probably it won't solve any of your problems, but maybe it humors you, at least to some extend. In my defense, I am a dad now, so I get to make jokes such as that one.




