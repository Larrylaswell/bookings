# The evolution of f(u)nctions

In the beginning . . .

The morning was bitter cold. Slicing wind gusts drifted snow to over two feet and had already blocked our front door. That is the way Monday January 19th 1983 began and, for me, it wasn’t going to get any better.  I worked as Director of development for Lycor Inc., an international software company providing life insurance administration software to life insurance companies in North America, Europe, Japan and the Pacific Rim. Our product, the Pallm System, contained over 200,000 lines of Cobol Code, (Cobol was the industry standard for programming languages at the time), and the entry-level license was a cool 1 million dollars plus and an annual fee of one hundred thousand for updates and maintenance.

The Pallm system was made up of reasonably structured modules arranged in a well-designed architecture. At the time, industry standards demanded modules be hierarchal and made up of packets (or “paragraphs”) of procedural programming code. For a client to install our semi-annual release of new features and bug fixes, a programmer would have to wedge packets of new code into one or more modules thereby calling the integrity of those modules into question.  In turn, the change required extensive testing for the new capability as well as regression testing to verify the overall system’s integrity.  This update process to a client’s system was time consuming and expensive, and the reason why our “updates and maintenance” program was at risk.  This was my problem.  We needed a better way.

Lycor, my employer, was an unusual company and the type most entrepreneurs only dream about.  Lycor had about 200 employees and hired about the same number of programmers each year.  Each year all but about 10 of the new employees would leave because they could not survive the fast-paced “get it done” culture of the company, or the knowledge standards of the employee base.  The company was a brain-trust in life insurance and technology; it was a challenging and fun environment.

On this particularly frigid morning I called eight of the company’s smartest from various disciplines to a meeting in the front conference room overlooking the blizzard outside.  I had two problems I needed to solve – hopefully my assembled group could come up a solution to my problems or maybe a hint to a solution as this group had done several times before.  When stated as a question, my two problems were:

1. How can we build a software system that is never changed, but can be expanded without changing anything in the existing system?

2. How can business managers define their products to a software system in a language they understand: i.e. English?

These two business questions give rise to the following technical questions.

1. How do you build flexible systems AND forbid program changes? 

2. How do you build a system with dozens, if not hundreds, of modules and thousands of lines of code such that the interface (read data communication) between all modules is the same despite the wide-ranging subject matter (read data) they handle? 

Sinple, Right? No! Try impossible.  But, some would say, “I thought with software you could construct anything that is describable.” True, but in this case the programming effort would be enormous, and the resulting program would run “forever” on the day’s fastest computers.  The only solution I could see was unacceptable. I put my questions to the group: they thought I was joking.  When assured the questions were serious, they couldn’t come up with so much as a smidgin of a hint of a solution.  To them, this was not an engineering problem, but a magic problem since as one of them pointed out, ”Any sufficiently advanced technology is indistinguishable from magic.”  All that was needed was a persistent search for the answers, a little luck, and a few small technology advances that when taken together would create magic.

A study of 20th century technology shows that those things we hailed as great technology advances such as the internet, computers and i-phones are not due to a single advance in technology but from numerous small incremental advances in different and often unassociated technologies. Knowing this my three-decade quest for the answers began. 

Over those years, (even during my stint as the CEO of a 2.3 Billion dollar brokerage) I kept my pulse on technology and kept pushing this problem through my head. Finally, in 2007, I built my first prototype to calculate the cash value of a complex life insurance policy.  It worked and ran faster than other systems.  Life interrupted my software quest for the next few years and in 2021 I built my second improved prototype.  It worked, but the computer language I picked was not up to the challenge.  Now I have started the construction of the f(u)nctions system.

This repository shows the progress toward the first production version of f(u)nctions system.

Larry
