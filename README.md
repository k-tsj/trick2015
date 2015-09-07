# TRICK 2015

The 2nd Transcendental Ruby Imbroglio Contest for rubyKaigi


## Goals of the TRICK

* To write the most Transcendental, Imbroglio Ruby program.
* To illustrate some of the subtleties (and design issues) of Ruby.
* To show the robustness and portability of Ruby interpreters.
* To stabilize the spec of Ruby by the presence of valuable but unmaintainable code.


## Rules

1. Your entry must be a complete Ruby program.
1. The size of your program must be <= 4096 bytes in length. The number of non-space characters must be <= 2048. The total size of your compressed submission must be less than ten megabyte in size.
1. You can submit multiple entries, and your team may consist of any number of members.
1. The entirety of your entry must be submitted under [MIT License](http://opensource.org/licenses/MIT).
1. Your entry must bring the judges a surprise, excitement, and/or laughter.


## Guidelines

These are not strict rules but hints or suggestions. You can ignore them but we'd recommend you to follow them.

* Matz Ruby Implementation (MRI) 2.2 is recommended.
* You can use implementations other than MRI, such as JRuby and Rubinius.
* The judges would prefer more stoic, more portable, and/or more funny entries.
* You are encouraged to examine the winners of previous [TRICK](https://github.com/tric/trick2013) and [IOCCC](http://ioccc.org).
* You can use a gem library.
  * Note that we will expect such entries to be much more interesting than an entry that uses no library; hence we will judge them strictly.
  * It is highly discouraged to abuse gem to get around the size limit.
* To judge without bias, we will try to keep each entry anonymous during judgment. Do not include anything that reveal your identity (such as a signature, copyright, URL, etc.) in your program.


## Important Dates

* 8th Sep.  2015: contest open
* 31st Oct. 2015: submission deadline
* 11th-13th Dec. 2015: result announcement (in RubyKaigi 2015, if accepted)


## How to submit

Your submission must consist of the following files:

* `entry.rb`
* `remarks.markdown`
* `authors.markdown`
* `Gemfile` and `Gemfile.lock` (if you user any gem library)
* data files (if any)

`remarks.markdown` must include the following information:

* Ruby implementation, version, platform that you use
  (it is a good idea to copy and paste the output of `ruby -v`)
* How to run

`authors.markdown` must include the following information (and the `remarks.markdown` must NOT have them):

* Your name (you can use handle)
* ccTLD of your country/region

Compress your entry as a zip file called entry.zip and send it to `trick.submit at gmail.com` as an attachment.

* You must include the words `TRICK 2015 submission` in the subject of your email.
* See an example of [entry.zip](entry.zip) that attached in this page.

If you have any question, please open a ticket in this repository, or send an e-mail to `trick.submit at gmail.com`.


## Winners

TBA.


## Judges

Alphabetical order.

* Yusuke Endoh ([@mametter][mametter]. Ruby committer. [IOCCC winner][ioccc_endoh].)
* Koichiro Eto ([@eto][eto]. Media Artist. [Chairman at NicoNicoGakkai Beta][niconicogakkai].)
* Shinichiro Hamaji ([@shinh][shinh]. [The admin of anarchy golf][golf]. [IOCCC winner][ioccc_shinh].)
* Yutaka Hara ([@yhara][yhara]. [The author of Japanese esolang book][esolangbook].)
* Sun Park (a.k.a. leonid. [The 1st super Ruby golfer][golfers].)
* Hirofumi Watanabe ([@eban][eban]. Ruby committer. [The 2nd super Ruby golfer][golfers].)
* ...

[mametter]: https://twitter.com/mametter
[eto]: https://twitter.com/eto
[shinh]: https://twitter.com/shinh
[yhara]: https://twitter.com/yhara
[eban]: https://twitter.com/eban
[ioccc_endoh]: http://www.ioccc.org/winners.html#Yusuke_Endoh
[ioccc_shinh]: http://www.ioccc.org/winners.html#Shinichiro_Hamaji
[niconicogakkai]: http://niconicogakkai.jp/
[golf]: http://golf.shinh.org/
[esolangbook]: http://esolang-book.route477.net/
[golfers]: http://golf.shinh.org/u.rb?rb


## Legal

This work is licensed under the MIT License.

    Copyright (c) 2015, TRICK Winners and Judges.
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.