# Smali

## types

```text
V    void - can only be used for return types
Z    boolean
B    byte
S    short
C    char
I    int
J    long (64 bits)
F    float
D    double (64 bits)
L    # Object type ex->Lpackage/name/ObjectName; java->package.name.ObjectName
ex ) Ljava/lang/String -> java.lang.String

#array 
[I -> int[] 
[I -> int[][] 
[Ljava/lang/String -> java.lang.String[]
```

## methods

```text
Lpackage/name/ObjectName;->MethodName(III)Z
(III) -> parameters  ( int , int , int )
Z -> return type 
method(I](i-->-int[][]-
[ljava/lang/string-->-java.lang.string[]
```

## -methods-

```text
lpackage/name/objectname;->methodname(iii)z
(iii)-->-parameters--(-int-,-int-,-int-)
z-->-return-type-
method(i.html)[IILjava/lang/String;[Ljava/lang/Object;)Ljava/lang/String;
String method(int, int[][], int, String, Object[])
```

## fields

```text
Lpackage/name/ObjectName;->FieldName:Ljava/lang/String;
object name -> method name -> type 

java.lang.String package.name.ObjectName.FieldName;
```

## get

```text
iget-object vo,po,xxxx
po -> this 
v0 =  this.xxx
```

\]\(iiljava/lang/string;\[ljava/lang/object;\)ljava/lang/string; string-method\(int,-int\[\]\[\],-int,-string,-object\[\]\)

```text
##-fields-
```

lpackage/name/objectname;-&gt;fieldname:ljava/lang/string; object-name--&gt;-method-name--&gt;-type-

java.lang.string-package.name.objectname.fieldname;

```text
##-get
```

iget-object-vo,po,xxxx po--&gt;-this- v0-=--this.xxx

\`\`\`

.html\)

