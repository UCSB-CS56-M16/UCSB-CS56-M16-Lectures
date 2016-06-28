# Notes for Tuesday 06.28

* Some discussion of lab00

Many of you (most of you) did not include the step in the build.xml
for creating the build directory.

Most of you also did not add the lib subdirectory with the junit jar file.

I can't blame you for this; I (your instructor, Phill Conrad) made the
same oversight when creating the example repo:

https://github.com/UCSB-CS56-M16/cs56-rational-example

However, I did correct my error on Piazza and go over the fix in lecture.

So, Hiranya and I discussed it, and here is what we are going to do:

* Later today, I will add some instructions to lab00 with
  a detailed grading rubric, including discussion that you must
  add the step to the build.xml for creating the build directory,
  and that you must have the junit jar in the lib subdirectory.

* More generally, it needs to be the case that as SOON as someone
  clones your directory, they can type `ant compile`, `ant run`, etc.
  and everything will just work.

* We will discuss how to make sure that this is the case.

* Then we'll open a two day extension on the assignment so that you
  can update your submissions before we calculate the final grades.

