# BracketLang
YAPLTPWBC - yet another programming language that probably won't be created

```
~~ this is a comment.

~>
this is a multiline comment

you see?

MULTIPLE LINES!!!


cool.
~<

(*{Class Person} | class[{
   (*{String firstname} | "<NO NAME>") 
   
   ~>
   default value is set by wrapping definition in * (parentheses are required because it is an expression in Brackets).
   ~<
   
   {String secondname} ~~ No default value provided
   {Int age}
  }
  {
  (*{Constructor $} | exec[{{String name} {String surname} {Int age}} {
   (_*{Instance inst} | _inst[type[Person]]) ~~ _* is same as just *, but _* is for metaobjects.
   inst{} ~~ inst means instance (can be anything)
  }])
  
  }
])
```
