---
marp: true
paginate: true
---

# Roslyn

---

# So what is Roslyn?
- open source <!-- although it seems it wasn't right from the beginning -->
- developed by Microsoft
- parse and analyse code
   - C#
   - Visual Basic
- used in Visual Studio

---
# What is the purpose of Roslyn?

<!--
a compiler produces a lot of information during the process of the compilation
they are only internally used while the compiler does it's work
after the compiler is finished all information is thrown away
the problem is that information would be very useful for things like
code analysis
code refactoring
and IntelliSense (IDE Editor)

until now you were able to control a Compiler from outside


Roslyn keeps that information and provides it to other tools over APIs


but what about the 
-->

---
# Disadvantages
- doesn't support C++
- not all internal information is available from the outside


---
# Sources
- [heise.de](https://www.heise.de/ix/artikel/Scheibenweise-1475294.html)
