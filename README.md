# Code Guidelines for Imaginate Projects

### Naming Convention

#### Use UpperCamelCase(PascalCase) naming style for Functions

##### Do
```C#
public Vector3 SomeFunctionName(){
	// Some procedure
}
```

##### Don't
```C#
public Vector3 someFunctionName(){  
	// Some procedure
}

#### Use lowerCamelCase naming style for parameters, member variables, global variables, local variables

##### Do
```C#
private float someFloatValue = 10.f;
private int someIntValue     = 10;
```

##### Don't
```C#
private float SomeFloatValue = 10.f;
private int someintvalue     = 10;
```

#### Use ALLCAPS naming style for Constants (separated by underscores)

##### Do
```C#
private const float FLOAT_CONSTANT = 10.f;
private const int INTEGER_CONSTANT = 10;
```
##### Don't
```C#
private const float floatconstant  = 10.f;
private const int integer_Constant = 10;
```