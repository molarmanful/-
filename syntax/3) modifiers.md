#Modifiers
##`()`
Use parentheses to join several words into a list.

```
[`(¹ ²) ⇌?]  (I,you) path-unknown => Where should you and I go?
```
##`{}`
Use curly brackets inside words to join roots inside a word.

```
[`¹ ⇌?{/←→}]  I path-unknown-{alternation-backward-forward} => Should I go backward or forward?
```
Notice that `{/←→}` describes `?`, and `←→` describe `/`.
##`A-Za-z`
Use any alphabetical character at the end of a word to "store" it as a variable. This is implemented to reduce pronoun ambiguities often present in many natural languages.

```
[`(¹ ² ³º)A ⇌£]  (I,you,it-male)=A path-left => You, he, and I go left.
[A ⇌¥]  A path-left => We go left.
```
##`«»`
Use double-angle quotes to insert foreign words and phrases.
