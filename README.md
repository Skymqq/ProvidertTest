# ProvidertTest
我们这里先假设先有一个A应用程序，这个程序中存在一个BookStore数据库和一张Book表，

然后还有一个B应用程序，跨程序实现数据共享的意思就是，通过B程序，我们可以对A程序中的Book表中的数据进行CRUD（增删改查）操作。

下面我们就一一来实现A应用程序和B应用程序。

A应用程序：DatabaseSave

B应用程序：ProviderTest

我们需要实现ProviderTest应用程序对DatabaseSave应用程序的CRUD操作。
