```

# single line comment

###
multiline
comment
###

var integerVariable = 0
val integerValue = integerVariable
val stringValue = "simple example"
val numberValueDefined = 3.14
val numberValueUndefined: number

val addToNumberFunction = (other: number): number => {
  return other + numberValueUndefined
}

val messageValue = {
  subject: "information for our subscribers"
  body: "we are glad to announce..."
}

type Message = {
  subject: string
  body: string
}

switch messageValue.type {
  Message {
    @("messageValue has type Message\n")
    @("adding #{val randomValue = random()} to #{numberValueUndefined} equal to #{addToNumberFunction(randomValue)}\n")
    @("if not overriden you should see all this in STDOUT")
  }
  undefined {
    @("messageValue is undefined; ")
  }
}

if numberValueUndefined.type != undefined {
  if numberValueDefined > numberValueUndefined || numberValueUndefined - numberValueDefined == 2.78 {
    @("else may be added")
  } else {
    @("to be invoked in case if condition is negative")
  }
}

switch message.subject {
  ""

}

```

###### comparison

| switch     | match      | result |
|------------|------------|--------|
| type A     | value of A | true   |
| value of A | type of A  | true   |
