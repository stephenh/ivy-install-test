
Running `ant install` results in:

    install:
    [ivy:install] :: Ivy 2.2.0 - 20100923230623 :: http://ant.apache.org/ivy/ ::
    [ivy:install] :: loading settings :: file = /home/stephen/foo/ivysettings.xml
    [ivy:install] :: installing commons-lang#commons-lang;2.3 ::
    [ivy:install] :: resolving dependencies ::
    [ivy:install] :: downloading artifacts to cache ::
    [ivy:install] :: installing in local ::
    [ivy:install] :: install resolution report ::
    [ivy:install] :: resolution report :: resolve 0ms :: artifacts dl 1ms
        ---------------------------------------------------------------------
        |                  |            modules            ||   artifacts   |
        |       conf       | number| search|dwnlded|evicted|| number|dwnlded|
        ---------------------------------------------------------------------
        |      default     |   1   |   0   |   0   |   0   ||   0   |   0   |
        ---------------------------------------------------------------------
    [ivy:install] 
    [ivy:install] :: problems summary ::
    [ivy:install] :::: WARNINGS
    [ivy:install]       ::::::::::::::::::::::::::::::::::::::::::::::
    [ivy:install]       ::          UNRESOLVED DEPENDENCIES         ::
    [ivy:install]       ::::::::::::::::::::::::::::::::::::::::::::::
    [ivy:install]       :: commons-lang#commons-lang;2.3: java.text.ParseException: inconsistent module descriptor file found in 'http://repo1.maven.org/maven2/commons-lang/commons-lang/2.3/commons-lang-2.3.pom': bad organisation: expected='commons-lang' found='apache'; 
    [ivy:install]       ::::::::::::::::::::::::::::::::::::::::::::::
    [ivy:install] :::: ERRORS
    [ivy:install]       maven: bad organisation found in http://repo1.maven.org/maven2/commons-lang/commons-lang/2.3/commons-lang-2.3.pom: expected='commons-lang' found='apache'
    [ivy:install] 
    [ivy:install] :: USE VERBOSE OR DEBUG MESSAGE LEVEL FOR MORE DETAILS

    BUILD FAILED
    /home/stephen/foo/build.xml:17: Problem happened while installing modules - see output for details


