# Pardon (Kotlin)

"Pardon" is a NATO Phonetic Alphabet Translator concept, implemented in various languages. Original implementation in Python ([here](https://github.com/komish/pardon)), the concept is to take a string and print out the phonetic representation of the string characters. 

This project is an initial foray into the Kotlin language for learning purposes, and should not be considered a marker of good Kotlin syntax, grammar, or concepts.

## Environment Details

At least, what is perceived to be potentially relevant

```
$ java -version
java version "10.0.1" 2018-04-17
Java(TM) SE Runtime Environment 18.3 (build 10.0.1+10)
Java HotSpot(TM) 64-Bit Server VM 18.3 (build 10.0.1+10, mixed mode)

$ kotlinc -version
info: kotlinc-jvm 1.2.51 (JRE 10.0.1+10)
```

## Compile

```
$ kotlinc pardon.kt -include-runtime -d pardon.jar
```

## Sample Execution

```
$ java -jar pardon.jar hello world hunter2
"hello"

	Hotel Echo Lima Lima Oscar

"world"

	Whiskey Oscar Romeo Lima Delta

"hunter2"

	Hotel Uniform November Tango Echo Romeo Two
```
