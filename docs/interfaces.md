# Interfaces and editor integrations

<i class="fa fa-hand-o-right"></i> [General index](/github) of other kdb+ repositories

Repositories at <i class="fa fa-github"></i> [KxSystems](https://github.com/KxSystems) are maintained and supported by Kx Systems. 
Other repositories are maintained by their owners. 

!!! warning "Salvaged repositories"
    <i class="fa fa-github"></i> [kxcontrib](https://github.com/kxcontrib) contains repositories salvaged from the former Subversion server for which we have been unable to identify current versions on GitHub. These repositories are not maintained. 

<div style="background-color: #efefef; border: 1px solid #005499; border-radius: 10px; display: inline-block; padding: 0 1em;" markdown="1">Please tell [librarian@kx.com](mailto:librarian@kx.com)
about new repositories.</div>


## <i class="fa fa-superpowers"></i> Fusion interfaces

The [Fusion interfaces](interfaces/fusion) to kdb+ are

-   written for non-kdb+ programmers to use
-   well documented, with understandable and useful examples
-   maintained and supported by Kx on a best-efforts basis, at no cost to customers
-   released under the [Apache 2 license](https://www.apache.org/licenses/LICENSE-2.0)
-   free for all use cases, including 64-bit and commercial use
<!-- -   written from the perspective of the ‘remote’ technology: e.g. a Java interface that is intelligible to a Java programmer -->

<table class="kx-compact" markdown="1">
<tr><td>FFI</td><td>[Using foreign functions with kdb+](/interfaces/ffi) ==new==</td></tr>
<tr><td>Java</td><td>[Java client for kdb+](/interfaces/java-client-for-q) ==updated==</td>
<tr><td>Kafka</td><td>[Q client for Kafka](/interfaces/kafka) ==new==</td></tr>
<tr><td>Python</td>
    <td>
[Using Python with kdb+ (PyQ)](/interfaces/pyq)<br/>
[Using Python with kdb+ (embedPy)](/interfaces/embedpy) ==beta==
    </td></tr>
<tr><td>R</td><td>[Using R with kdb+](/interfaces/with-r/#calling-q-from-r) ==new==</td>
</tr>
</table>


## <i class="fa fa-server"></i> Kdb+ as server

<table class="kx-compact" markdown="1">
<tr><td>Adobe Flex</td><td><i class="fa fa-github"></i> [quantbin/kdb](https://github.com/quantbin/kdb)</td></tr>
<tr>
    <td>ADO.Net</td>
    <td>
<i class="fa fa-github"></i> [ScottWeinstein/Linq2KdbQ](https://github.com/ScottWeinstein/Linq2KdbQ)<br/>
<i class="fa fa-github"></i> [sv/kp.net](https://github.com/sv/kp.net)
    </td>
</tr>
<tr><td>amCharts</td><td><i class="fa fa-github"></i> [kxcontrib/cburke/amcharts](https://github.com/kxcontrib/cburke/tree/master/amcharts/)</td></tr>
<tr><td>AQuery</td><td><i class="fa fa-github"></i> [josepablocam/aquery](https://github.com/josepablocam/aquery) ==new==</td></tr>
<tr><td>C</td><td>[C client for kdb+](/interfaces/c-client-for-q)</td></tr>
<tr><td>CZMQ</td><td><i class="fa fa-github"></i> [jaeheum/qzmq](https://github.com/jaeheum/qzmq)</i></td></tr>
<tr><td>C#</td><td>[C# client for kdb+](/interfaces/csharp-client-for-q/)<br/>
<i class="fa fa-github"></i> [exxeleron/qSharp](https://github.com/exxeleron/qSharp)</td></tr>
<tr>
    <td>Erlang</td>
    <td>
<i class="fa fa-github"></i> [exxeleron/qErlang](https://github.com/exxeleron/qErlang/)<br/>
<i class="fa fa-github"></i> [republicwireless-open/gen_q](https://github.com/republicwireless-open/gen_q)<br/>
<i class="fa fa-github"></i> [michaelwittig/erlang-q](https://github.com/michaelwittig/erlang-q)
    </td>
</tr>
<tr>
    <td>Excel</td>
    <td>
[Excel client for kdb+](interfaces/excel-client-for-q/)<br/>
<i class="fa fa-github"></i> [exxeleron/qXL](https://github.com/exxeleron/qXL)<br/>
<i class="fa fa-github"></i> [CharlesSkelton/excelrtd](https://github.com/exxeleron/qXL)
    </td>
</tr>
<tr><td>F#</td><td><i class="fa fa-github"></i> [kimtang/c.fs](https://github.com/kimtang/c.fs)</td></tr>
<tr><td>Go</td><td><i class="fa fa-github"></i> [sv/kdbgo](https://github.com/sv/kdbgo)</td></tr>
<tr>
    <td>Haskell</td>
    <td>
<i class="fa fa-github"></i> [carrutstick/hasq](https://github.com/carrutstick/hasq)<br/>
<i class="fa fa-github"></i> [jkozlowski/kdb-haskell](https://github.com/jkozlowski/kdb-haskell)
    </td>
</tr>
<tr><td>IntelliJ IDEA</td><td><i class="fa fa-github"></i> [k-intellij-plugin](https://github.com/a2ndrade/k-intellij-plugin) ==new==</td></tr>
<tr><td>J</td><td>[J client for kdb+](/interfaces/j-client-for-q/)</td></tr>
<tr>
    <td>Java</td>
    <td>
<i class="fa fa-github"></i> [CharlesSkelton/jshow](https://github.com/CharlesSkelton/jshow)<br/>
<i class="fa fa-github"></i> [exxeleron/qJava](https://github.com/exxeleron/qJava)<br/>
<i class="fa fa-github"></i> [michaelwittig/java-q](https://github.com/michaelwittig/java-q)
    </td>
</tr>
<tr>
    <td>JDBC</td>
    <td>[JDBC client for kdb+](/interfaces/jdbc-client-for-kdb/)</td>
</tr>
<tr>
    <td>JavaScript</td>
    <td>
[WebSockets](/cookbook/websockets)<br/>
<i class="fa fa-github"></i> [KxSystems/kdb/c/c.js](https://github.com/KxSystems/kdb/blob/master/c/c.js)<br/>
<i class="fa fa-github"></i> [kxcontrib/cbutler/ChartsForKdb](https://github.com/kxcontrib/cbutler/tree/master/ChartsForKdb)<br/>
<i class="fa fa-github"></i> [MdSalih/Kdb-Stuff/IPCWebParse](https://github.com/MdSalih/Kdb-Stuff/tree/master/IPCWebParse)<br/>
<i class="fa fa-github"></i> [michaelwittig/java-q](https://github.com/michaelwittig/java-q)
    </td>
</tr>
<tr><td>Lua</td><td><i class="fa fa-github"></i> [geocar/qlua](https://github.com/geocar/qlua)</td></tr>
<tr>
    <td>Mathematica</td>
    <td>
        <i class="fa fa-github"></i> [KxSystems/kdb/c/other/qmathematica.txt](https://github.com/KxSystems/kdb/blob/master/c/other/qmathematica.txt)
    </td>
</tr>
<tr><td>Matlab</td>
<td>
[Matlab client for kdb+](/interfaces/matlab-client-for-q/)<br/>
<i class="fa fa-github"></i> [dmarienko/kdbml](https://github.com/dmarienko/kdbml)</td></tr>
<tr><td>NaCL</td><td><i class="fa fa-github"></i> [geocar/qsalt](https://github.com/geocar/qsalt)</td></tr>
<tr>
    <td>NodeJS</td>
    <td>
<i class="fa fa-github"></i> [geocar/qnode](https://github.com/geocar/qnode)<br/>
<i class="fa fa-github"></i> [michaelwittig/node-q](https://github.com/michaelwittig/node-q)
    </td>
</tr>
<tr><td>ODBC</td><td>[Kdb+ server for ODBC](/interfaces/q-server-for-odbc/)<br/>
[Kdb+ server for ODBC3](/interfaces/q-server-for-odbc3/)</td></tr>
<tr>
    <td>Perl</td>
    <td>
[Perl client for kdb+](/interfaces/perl-client-for-q/)<br/>
<i class="fa fa-github"></i> [wjackson/anyevent-k](https://github.com/wjackson/anyevent-k)<br/>
<i class="fa fa-github"></i> [wjackson/k-perl](https://github.com/wjackson/k-perl)
    </td>
</tr>
<tr>
    <td>PHP</td>
    <td>
<i class="fa fa-github"></i> [geocar/qphp](https://github.com/geocar/qphp)<br/>
<i class="fa fa-github"></i> [johnanthonyludlow/kdb/docs/phptoq.pdf](https://github.com/johnanthonyludlow/kdb/blob/master/docs/phptoq.pdf)
    </td>
</tr>
<tr><td>PLplot</td><td><i class="fa fa-github"></i> [jaeheum/qplplot](https://github.com/jaeheum/qplplot)</td></tr>
<tr><td>Python</td>
    <td>
<!-- [Using Python with kdb+](/interfaces/with-python/)<br/> -->
<i class="fa fa-github"></i> [brogar/pykdb](https://github.com/brogar/pykdb)<br/>
<i class="fa fa-github"></i> [enlnt/pyk](https://github.com/enlnt/pyk)<br/>
<!-- <i class="fa fa-github"></i> [enlnt/pyq](https://github.com/enlnt/pyq)<br/> -->
<i class="fa fa-github"></i> [eschnapp/q](https://github.com/eschnapp/q)<br/>
<i class="fa fa-github"></i> [nugend/q](https://github.com/nugend/q)<br/>
<i class="fa fa-github"></i> [nugend/qPython](https://github.com/nugend/qPython)<br/>
<i class="fa fa-github"></i> [exxeleron/qPython](https://github.com/exxeleron/qPython)<br/>
<i class="fa fa-github"></i> [kingan/mongodb_kdb_python_connection](https://github.com/kingan/mongodb_kdb_python_connection)
    </td></tr>
<tr><td>R</td><td><i class="fa fa-github"></i> [yang-guo/qserver](https://github.com/yang-guo/qserver)</td></tr> 
<tr>
    <td>Rust</td>
    <td>
<i class="fa fa-github"></i> [adwhit/krust](https://github.com/adwhit/krust)<br/>
<i class="fa fa-github"></i> [jnordwick/rik](https://github.com/jnordwick/rik)
    </td>
</tr>
<tr><td>Scala</td><td>[Scala client for kdb+](/interfaces/scala-client-for-q/)</td></tr>
</table>


## <i class="fa fa-handshake-o"></i> Q as client

<table class="kx-compact" markdown="1">
<tr><td>Betfair</td><td><i class="fa fa-github"></i> [picoDoc/betfair-data-capture](https://github.com/picoDoc/betfair-data-capture)</td></tr>
<tr><td><i class="fa fa-bitcoin"></i> Bitcoin</td><td><i class="fa fa-github"></i> [bitmx/btceQ](https://github.com/bitmx/btceQ)</td></tr>
<tr><td>Bloomberg</td><td>[Q client for Bloomberg](/interfaces/q-client-for-bloomberg)</td></tr>
<tr><td>[BosonNLP](http://bosonnlp.com/)</td><td><i class="fa fa-github"></i> [FlyingOE/q_BosonNLP](https://github.com/FlyingOE/q_BosonNLP) ==new==</td></tr>
<tr><td>CUDA</td><td>[GPUs](/interfaces/gpus/)</td></tr>
<tr><td>Expat XML parser</td><td><i class="fa fa-github"></i> [felixlungu/qexpat](https://github.com/felixlungu/qexpat)</td></tr>
<tr><td>[Factom](https://www.factom.com/) blockchain</td><td><i class="fa fa-github"></i> [jlucid/qfactom](https://github.com/jlucid/qfactom) ==new==</td></tr>
<tr><td>ForexConnect</td><td><i class="fa fa-github"></i> [mortensorensen/qfxcm](https://github.com/mortensorensen/qfxcm)</td></tr>
<tr><td>Interactive Brokers</td><td><i class="fa fa-github"></i> [mortensorensen/QInteractiveBrokers](https://github.com/mortensorensen/QInteractiveBrokers)</td></tr>
<tr><td>J</td><td>[Q client for J](/interfaces/q-client-for-j/)</td></tr>
<tr><td>JDBC</td><td><i class="fa fa-github"></i> [CharlesSkelton/babel](https://github.com/CharlesSkelton/babel)</i></td></tr>
<tr><td>ODBC</td><td>[Q client for ODBC](/interfaces/q-client-for-odbc)<br/>
<i class="fa fa-github"></i> [johnanthonyludlow/kdb/docs/odbc.pdf](https://github.com/johnanthonyludlow/kdb/blob/master/docs/odbc.pdf)</td></tr>
<tr><td>Philips Hue</td><td><i class="fa fa-github"></i> [jparmstrong/qphue](https://github.com/jparmstrong/qphue)</td></tr>
<tr><td>R</td><td>[Using R with kdb+](/interfaces/with-r/#calling-r-from-q)</td></tr>
<tr><td>Reuters</td><td><i class="fa fa-github"></i> [KxSystems/kdb/c/feed/rfa.zip](https://github.com/KxSystems/kdb/blob/master/c/feed/rfa.zip)</td></tr>
<tr><td>TSE FLEX</td><td><i class="fa fa-github"></i> [Naoki-Yatsu/TSE-FLEX-Converter](https://github.com/Naoki-Yatsu/TSE-FLEX-Converter)</td></tr>
<tr><td><i class="fa fa-twitter"></i> Twitter</td><td><i class="fa fa-github"></i> [gartinian/kdbTwitter](https://github.com/gartinian/kdbTwitter)</td></tr>
<tr><td>[Wind资讯](http://www.wind.com.cn/en/)</td><td><i class="fa fa-github"></i> [FlyingOE/q_Wind](https://github.com/FlyingOE/q_Wind)</td></tr>
<tr><td><i class="fa fa-yahoo"></i> Yahoo!</td><td><i class="fa fa-github"></i> [fdeleze/tickYahoo](https://github.com/fdeleze/tickYahoo)</td></tr>
</table>



## <i class="fa fa-map-signs"></i> Foreign functions 

<table class="kx-compact" markdown="1">
<tr><td>[Boost](http://www.boost.org/) math library</td><td><i class="fa fa-github"></i> [kimtang/bml](https://github.com/kimtang/bml)</td></tr>
<tr>
    <td>C/C++</td>
    <td>
[Using C/C++ functions](interfaces/using-c-functions)<br/>
<i class="fa fa-github"></i> [enlnt/ffiq](https://github.com/enlnt/ffiq)<br/>
<i class="fa fa-github"></i> [felixlungu/c](https://github.com/felixlungu/c)
    </td>
</tr>
<tr><td>Fortran</td><td><i class="fa fa-github"></i> [johnanthonyludlow/kdb/docs/fortran.pdf](https://github.com/kxcontrib/jludlow/blob/master/docs/fortran.pdf)</td></tr>
<tr><td>gnuplot</td><td><i class="fa fa-github"></i> [kxcontrib/zuoqianxu/qgnuplot](https://github.com/kxcontrib/zuoqianxu/tree/master/qgnuplot)</td></tr>
<tr><td>Google Charts</td><td><i class="fa fa-github"></i> [kxcontrib/zuoqianxu/qgooglechart](https://github.com/kxcontrib/zuoqianxu/tree/master/qgooglechart)</td></tr>
<tr><td>LAPACK, Cephes and FDLIBM</td><td>[althenia.net/qml](http://althenia.net/qml)</td></tr>
<tr><td>Mathematica</td><td><i class="fa fa-github"></i> [kxcontrib/zuoqianxu/qmathematica](https://github.com/kxcontrib/zuoqianxu/tree/master/qmathematica)</td></tr>
<tr><td>Matlab</td><td><i class="fa fa-github"></i> [kxcontrib/zuoqianxu/qmatlab](https://github.com/kxcontrib/zuoqianxu/tree/master/qmatlab)</td></tr>
<tr><td>Perl</td><td><i class="fa fa-github"></i> [kxcontrib/zuoqianxu/qperl](https://github.com/kxcontrib/zuoqianxu/tree/master/qperl)</td></tr>
<tr><td>Python</td><td>
<i class="fa fa-github"></i> [kxcontrib/serpent.speak](https://github.com/kxcontrib/serpent.speak)<br/>
<i class="fa fa-github"></i> [kxcontrib/zuoqianxu/qpython](https://github.com/kxcontrib/zuoqianxu/tree/master/qpython)
</td></tr>
<tr><td>Non-linear least squares</td><td><i class="fa fa-github"></i> [brogar/nls](https://github.com/brogar/nls)</td></tr>
<tr><td>Regular Expressions</td><td>[Regex libraries](/cookbook/regex/#regex-libraries)</td></tr>
<tr><td>R</td><td><i class="fa fa-github"></i> [kimtang/rinit](https://github.com/kimtang/rinit)<br/>
<i class="fa fa-github"></i> [rwinston/kdb-rmathlib](https://github.com/rwinston/kdb-rmathlib)</td></tr>
<tr><td>Rust</td><td><i class="fa fa-github"></i> [adwhit/krust](https://github.com/adwhit/krust)</td></tr>
<tr><td>TA-Lib</td><td><i class="fa fa-github"></i> [kxcontrib/zuoqianxu/qtalib](https://github.com/kxcontrib/zuoqianxu/tree/master/qtalib)</td></tr>
<tr><td>ZeroMQ</td><td><i class="fa fa-github"></i> [wjackson/qzmq](https://github.com/wjackson/qzmq)</td></tr>
</table>


## <i class="fa fa-plug"></i> Editor integrations

<table class="kx-compact" markdown="1">
<tr>
    <td>Atom</td>
    <td>
<i class="fa fa-github"></i> [derekwisong/atom-q](https://github.com/derekwisong/atom-q)<br/>
<i class="fa fa-github"></i> [quintanar401/atom-charts](https://github.com/quintanar401/atom-charts)<br/>
<i class="fa fa-github"></i> [quintanar401/connect-kdb-q](https://github.com/quintanar401/connect-kdb-q)
    </td>
</tr>
<tr><td>Eclipse</td><td>[qkdt.org](http://www.qkdt.org/features.html)</td></tr>
<tr><td>Emacs</td>
    <td>
<i class="fa fa-github"></i> [eepgwde/kdbp-mode](https://github.com/eepgwde/kdbp-mode) ==new==<br/>
<i class="fa fa-github"></i> [geocar/kq-mode](https://github.com/geocar/kq-mode)<br/>
<i class="fa fa-github"></i> [indiscible/emacs](https://github.com/indiscible/emacs)<br/>
<i class="fa fa-github"></i> [psaris/q-mode](https://github.com/psaris/q-mode)
    </td>
</tr>
<tr><td>Evolved</td><td><i class="fa fa-github"></i> [simongarland/Syntaxhighlighter-for-q](https://github.com/simongarland/Syntaxhighlighter-for-q)</td></tr>
<tr><td>Heroku</td><td><i class="fa fa-github"></i> [gargraman/heroku-buildpack-kdb](https://github.com/gargraman/heroku-buildpack-kdb)</td></tr>
<tr><td>Jupyter</td>
    <td>
<i class="fa fa-github"></i> [jvictorchen/IKdbQ](https://github.com/jvictorchen/IKdbQ)<br/>
<i class="fa fa-github"></i> [newtux/KdbQ_kernel](https://github.com/newtux/KdbQ_kernel)
    </td></tr>
<tr><td>Linux, macOS, Unix</td><td><i class="fa fa-github"></i> [enlnt/kdb-magic](https://github.com/enlnt/kdb-magic)</td></tr>
<tr><td>Pygments</td><td><i class="fa fa-github"></i> [jasraj/q-pygments](https://github.com/jasraj/q-pygments)</td></tr>
<tr>
    <td>Sublime Text</td>
    <td>
<i class="fa fa-github"></i> [kimtang/QStudio](https://github.com/kimtang/QStudio)<br/>
<i class="fa fa-github"></i> [kimtang/sublime-q](https://github.com/kimtang/sublime-q)<br/>
<i class="fa fa-github"></i> [kimtang/Q](https://github.com/kimtang/Q)<br/>
<i class="fa fa-github"></i> [komsit37/sublime-q](https://github.com/komsit37/sublime-q)
    </td>
</tr>
<tr>
    <td>vim</td>
    <td>
<i class="fa fa-github"></i> [katusk/vim-qkdb-syntax](https://github.com/katusk/vim-qkdb-syntax)<br/>
<i class="fa fa-github"></i> [patmok/qvim](https://github.com/patmok/qvim)<br/>
<i class="fa fa-github"></i> [simongarland/vim](https://github.com/simongarland/vim)
    </td>
</tr>
<tr>
    <td>Visual Studio Code</td><td><i class="fa fa-github"></i> [lwshang/vscode-q](https://github.com/lwshang/vscode-q) ==new==</td>
</tr>
</table>

