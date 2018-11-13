# Scala And Spark

Welcome everybody. Because bookemarks are too confidentials, at Paris 13 university, we decided to share every usefull links we fall on during our ongoing learning of Scala and Spark, trying to organize them as well as we can. Don't hesitate to add cool links we have missed.

Some comments will be added with time :smile: !

# [Scala](https://www.scala-lang.org/)

[Use it wisely](http://www.scala-lang.org/api/current/#package), don't forget to go for a [tour](https://docs.scala-lang.org/tour/tour-of-scala.html) and if you're ready go directly to the famous [awesome-scala](https://github.com/lauris/awesome-scala) github regrouping most starred scala projects.

## Learn by practicing

* Learn Scala standard library and some frameworks through [exercising](https://www.scala-exercises.org/)

## Overviews

* [Because we have to begin somewhere](https://www.scala-exercises.org/)
* [The Neophyte's Guide to Scala](http://danielwestheide.com/scala/neophytes.html)
* [Tweeter Scala School](https://twitter.github.io/scala_school/index.html)
* [Scala cheatsheet](https://mbonaci.github.io/scala/) from a java point of view

## Specifics aspects

* **Keywords**
  * **for with conditions**
    * [alvinalexander Blog](https://alvinalexander.com/scala/how-to-for-loop-embedded-if-statements-guards-scala)
  * **for yield**
    * [alvinalexander Blog](https://alvinalexander.com/scala/scala-for-loop-yield-examples-yield-tutorial)
  * **lazy**
    * [What does a lazy val do ?](https://stackoverflow.com/questions/7484928/what-does-a-lazy-val-do)
    * [Interesting explanations](https://blog.codecentric.de/2016/02/lazy-vals-scala-look-hood/)
  * **[implicits]**
    * [Scala tour](https://docs.scala-lang.org/tour/implicit-parameters.html)
    * [Where does Scala look for implicits ?](https://stackoverflow.com/questions/5598085/where-does-scala-look-for-implicits)
    * [implicit design pattern](http://www.lihaoyi.com/post/ImplicitDesignPatternsinScala.html)
* **Collection**
  * Some practical [advices](https://abstractionextraction.wordpress.com/2014/04/12/a-simple-view-of-scala-sequences/)
  * [Hints](https://alvinalexander.com/scala/understanding-performance-scala-collections-classes-methods-cookbook) about collection operations complexity
* **Class**
  * [Overview](https://alvinalexander.com/scala/scala-class-examples-constructors-case-classes-parameters)
* **Option** or the nice way to avoid null
    * http://danielwestheide.com/blog/2012/12/19/the-neophytes-guide-to-scala-part-5-the-option-type.html
    * http://code.scottshipp.com/2015/04/17/scala-using-option-can-still-result-in-a-npe/
* **Closure**
  * [Here](https://www.tutorialspoint.com/scala/scala_closures.htm) is an example and an explanation.
* **Generics**
  * [Class](https://docs.scala-lang.org/tour/generic-classes.html)
  * [Functions](https://docs.scala-lang.org/tour/polymorphic-methods.html)
* **Tail recursiv functions**
* **Covariance and Contravariance**
  * [Scala tour](https://docs.scala-lang.org/tour/variances.html)**
  * http://blog.kamkor.me/Covariance-And-Contravariance-In-Scala/
  * https://twitter.github.io/scala_school/type-basics.html
  * https://apiumhub.com/tech-blog-barcelona/scala-generics-covariance-contravariance/
  * https://www.atlassian.com/blog/software-teams/covariance-and-contravariance-in-scala
  * http://julien.richard-foy.fr/blog/2013/02/21/be-friend-with-covariance-and-contravariance/
* **Concurency**
  * https://blog.mathewrathbone.com/2017/03/28/scala-concurrency-options.html
* **[Did you said monad ?](https://en.wikipedia.org/wiki/Monad_(functional_programming))**
  * http://blog.brakmic.com/writing-monads-in-scala-with-spark-notebook/

### Annotations

* **@transient**
* **@specialized**
  * [Type specialization](https://dzone.com/articles/type-specialization-in-scala)
  * [One StackOverFlow](https://stackoverflow.com/questions/39526409/correct-use-of-specialized-in-scala)
  * [Another blog post on it](https://blog.scalac.io/2017/05/25/scala-specialization.html)
  * [More advanced examples](http://aleksandar-prokopec.com/2013/11/03/specialization-quirks.html)

## Frameworks 

* **[Awesome scala](https://github.com/lauris/awesome-scala)**, refer many many awesome projects in scala
* **[Smile :smile:](https://haifengl.github.io/smile/)** which is way more than a nicely named Scala/Java library for machine learning.
* **[Scalaz](https://github.com/scalaz/scalaz)**, an extension of the standard scala library that allow to do [pure functional programming](https://www.quora.com/What-is-Scalaz-useful-for)
  * [Multiple ressources](http://hacking-scala.org/post/49050104489/scalaz-resources-for-beginners)
  * [An introduction](http://noelmarkham.github.io/scalaz-intro/#/)
  * [An adventure to learn scalaz](http://eed3si9n.com/learning-scalaz/index.html)
* **[Breeze](https://github.com/scalanlp/breeze)**
  * [API](http://www.scalanlp.org/api/breeze/#breeze.package)
  * [Quickstart](https://github.com/scalanlp/breeze/wiki/Quickstart)
  * [Linear Algebra Cheat Sheet](https://github.com/scalanlp/breeze/wiki/Linear-Algebra-Cheat-Sheet)
* **[Spire](https://github.com/non/spire)**
* **[Scala.js](https://www.scala-js.org/)**

## Benchmarking Scala collections

Because we hardly desire to know the commodities comming with our favorite scala's collections here are some linked ressources:
* [Benchmarking Scala Collections](http://www.lihaoyi.com/post/BenchmarkingScalaCollections.html)
* [Performance Comparison between immutable Seq, List, Vector](https://danielasfregola.com/2015/06/15/which-immutable-scala-collection/)

## Design Patterns

* [Awesome article by Hayoi](http://www.lihaoyi.com/post/OldDesignPatternsinScala.html)
* [Another cool article on multiple patterns](https://pavelfatin.com/design-patterns-in-scala/)
* [The @transient lazy pattern](http://fdahms.com/2015/10/14/scala-and-the-transient-lazy-val-pattern/)
* [A master thesis on different patterns](https://www.scala-lang.org/old/sites/default/files/FrederikThesis.pdf)
* [Implicits patterns](http://www.lihaoyi.com/post/ImplicitDesignPatternsinScala.html)
* [Patterns with implementation](https://github.com/jfaerman/scala-patterns)
* [Stackable Trait Pattern](https://www.artima.com/scalazine/articles/stackable_trait_pattern.html)
* **Type Classes**
  * [Example 1](https://alvinalexander.com/scala/fp-book/type-classes-101-introduction)
  * [Example 2](https://danielwestheide.com/blog/2013/02/06/the-neophytes-guide-to-scala-part-12-type-classes.html)
  * [Example 3](https://blog.scalac.io/2017/04/19/typeclasses-in-scala.html)

## Miscellaneous

* [Union Types](http://milessabin.com/blog/2011/06/09/scala-union-types-curry-howard/)
* [Equivalence between Java and Scala](http://rea.tech/java-to-scala-cheatsheet/)
* [Returning the "Current" Type](https://tpolecat.github.io/2015/04/29/f-bounds.html)
* [Advanced Types](https://twitter.github.io/scala_school/advanced-types.html#fbounded)
* [99 Scala Problems](http://blog.thedigitalcatonline.com/blog/2015/04/07/99-scala-problems-05-reverse/#series)
* [One of many advantage of Spire](https://typelevel.org/blog/2013/07/07/generic-numeric-programming.html)
* [Higher-kinded types: the difference between giving up, and moving forward](https://typelevel.org/blog/2016/08/21/hkts-moving-forward.html)
* [A simpler way to returning the "current" type in Scala](https://gist.github.com/odersky/56323c309a186cffe9af)

## [Sbt](https://www.scala-sbt.org/)

* **[Multi-projects](https://www.scala-sbt.org/1.x/docs/Multi-Project.html)**
  * [An example of a sbt multi-project](https://github.com/aaronp/multi-project)
  * [A bit of explanations](https://alvinalexander.com/scala/how-to-create-sbt-projects-with-subprojects)
* sbt publish errors while compile works, try to clean you .ivy2/local/yourProject

## Before introduce Spark, i will recomand to you the [SparkNotebook](https://github.com/spark-notebook/spark-notebook)

So why introduce a first appearance Spark tool, simply because it offers multiple usefull functionalities to practice as well **Scala** as **Spark** for any kind of purposes. You will find complementary informations on the SparkNotebook creator compagny [blog](https://blog.kensu.io/).

# [Spark](https://spark.apache.org/)

Let's start with the **[official website guides](http://spark.apache.org/docs/latest/quick-start.html)** without forgetting to give the link towards the **[Databricks blog](https://databricks.com/blog)** and for impatients the usefull **[awesome-spark](https://github.com/awesome-spark/awesome-spark)** and **[spark-packages](https://spark-packages.org/)** links.

## General learning purpose

* https://jaceklaskowski.gitbooks.io/mastering-apache-spark/
* https://www.gitbook.com/book/jaceklaskowski/mastering-apache-spark/details

## Specifics aspects

  * **[Caching and Persistance](https://jaceklaskowski.gitbooks.io/mastering-apache-spark/content/spark-rdd-caching.html)**
  * **[Broadcast variables](https://jaceklaskowski.gitbooks.io/mastering-apache-spark/content/spark-broadcast.html)**
  * **[Accumulators](http://imranrashid.com/posts/Spark-Accumulators/)**
  * **ByKey methods**
    * **ReduceByKey**
      * [How it works](https://stackoverflow.com/questions/30145329/reducebykey-how-does-it-work-internally)
    * **Why avoid [GroupByKey](https://databricks.gitbooks.io/databricks-spark-knowledge-base/content/best_practices/prefer_reducebykey_over_groupbykey.html)**
    * **[AggregateByKey](http://codingjunkie.net/spark-agr-by-key/)**
    * **CombineByKey**
      * Examples [one](https://www.google.fr/search?q=combineBykey&oq=combineBykey&aqs=chrome..69i57j35i39j0l4.2345j0j4&sourceid=chrome&ie=UTF-8) [two](http://abshinn.github.io/python/apache-spark/2014/10/11/using-combinebykey-in-apache-spark/) and [three](http://codingjunkie.net/spark-combine-by-key/)
  * **[Why prefer mapPartitions over map](https://martin.atlassian.net/wiki/spaces/lestermartin/blog/2016/05/19/67043332/why+spark+s+mapPartitions+transformation+is+faster+than+map+calls+your+function+once+partition+not+once+element)**


## MLLib examples

* [Pipelines](http://www.sparktutorials.net/Spark+MLLib+-+Predict+Store+Sales+with+ML+Pipelines)
* **Some troubleshootings**
  * [Use non serializable objects](https://www.nicolaferraro.me/2016/02/22/using-non-serializable-objects-in-apache-spark/)
  * [Heavy workloads common issues](https://developer.ibm.com/hadoop/2016/07/18/troubleshooting-and-tuning-spark-for-heavy-workloads/)

## Miscellaneous

* [Parse your csv](http://carminedimascio.com/2015/02/apache-spark-convert-csv-to-rdd/)
* [Adjust your log levels](https://mapr.com/blog/how-log-apache-spark/)
* [Tuning your spark applications](http://evertrue.github.io/blog/2015/03/20/tuning-guidelines-for-apache-spark/)

### Cool projects

* [TSNE on spark](https://github.com/saurfang/spark-tsne), the TSNE is a dimentional reduction technique from the [manifold](https://en.wikipedia.org/wiki/Manifold) family
* [LIPN on Spark](https://github.com/Spark-clustering-notebook)
  * This is what we are making to Paris 13 University on Spark

# Garbage collector optimizations

## General informations and tuning

* [Managing Memory and Garbage Collection](https://docs.oracle.com/cd/E19159-01/819-3681/6n5srlhqf/index.html)
* [Minimize Java Memory Usage with the Right Garbage Collector](https://www.javacodegeeks.com/2017/11/minimize-java-memory-usage-right-garbage-collector.html)
* [Tuning G1GC For SOA](http://www.ateam-oracle.com/tuning-g1gc-for-soa/)
* [G1Gc Tuning](https://www.oracle.com/technetwork/articles/java/g1gc-1984535.html)
* [Others G1 GC tests](https://mpouttuclarke.wordpress.com/2013/03/13/large-java-heap-with-g1-collector-part-1/)

## Spark applications

* [Tuning Java Garbage Collection for Apache Spark Applications](https://databricks.com/blog/2015/05/28/tuning-java-garbage-collection-for-spark-applications.html)

# [Awesome scala](https://github.com/lauris/awesome-scala) links and references

Here are listed some blogs from where cames links in this page, thanks to these guys we can learn more easily so thank you for you hard work dear scala fellas :wink:.
* Books
  * [Programming in Scala 3rd Edition](https://www.amazon.co.uk/Programming-Scala-3rd-Martin-Odersky/dp/0981531687) let's start by [Scala's father](https://en.wikipedia.org/wiki/Martin_Odersky) last edition book.
  * [Functional Programming in Scala](https://www.manning.com/books/functional-programming-in-scala)
  * [A Spark online book](https://www.gitbook.com/book/jaceklaskowski/mastering-apache-spark/details)
* Blogs
  * [Twitter Scala School](https://twitter.github.io/scala_school/index.html)
  * [An awesome blog](http://www.lihaoyi.com/)
  * [Scala Cookbook author blog](https://alvinalexander.com/scala)
  * http://danielwestheide.com/blog/archives/
  * [Databricks blog](https://databricks.com/blog)

# [Scala.js](https://www.scala-js.org/)

* [Hands on Scala.js](http://www.lihaoyi.com/hands-on-scala-js/#IntrotoScala.js)
* [Scala-js-d3](https://github.com/spaced/scala-js-d3)
* [Getting started](https://medium.com/@michaelmangial1/getting-started-with-scala-js-scalavue-and-scalareact-for-the-javascript-developer-ac578ddcb5a8)