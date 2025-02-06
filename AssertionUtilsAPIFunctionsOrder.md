NOTES: DO NOT CHANGE THE FACT IVE DONE IT assertType or assertClass as opposed to classAssert, I'VE DONE IT THAT WAY FOR A REASON!

## Key Functions

AssertionUtils:safeAssert<T>(value: T, errorMessage: string?): (T?, string?)
* Description: returns error message or default one if provided value results to false or nil, it will not stop code workflow.

AssertionUtils:safeAsserts(valuesTable: {any}, errorMessage: string?): ({any}?, string?)

----
AssertionUtils:safeWarnAssert<T>(value: T, warnMessage: string?): (T?, string?)
* Description: returns error message or default one if provided value results to false or nil, it will not stop code workflow, however warning will come.

AssertionUtils:safeWarnAsserts(valuesTable: {any}, warnMessage: string?): ({any}?, string?)

----
## Callback

AssertionUtils:callbackAssert<T>(value: T, errorMessage: string?, callbackFunc: Function<(any), (any)>): T
* Description: If provided value results to false or nil then the callbackFunc will be called

AssertionUtils:callbackAsserts(

----
AssertionUtils:safeCallbackAssert<T>(value: T, errorMessage: string?, callbackFunc: Function<(any), (any)>): (T?, string?, any)

AssertionUtils:safeCallbackAsserts(

----
AssertionUtils:safeWarnCallbackAssert<T>(value: T, warnMessage: string?, callbackFunc: Function<(any), (any)>): (T?, string?, any)

AssertionUtils:safeWarnCallbackAsserts

----
## Special Asserts
These are ones where the value provided as a specific argument to the specific check are passed back if not resulted to false or nil, such as the type checking one, where the given object is provided as an argument, then the type is provided from there, then returning the object arg, which is useful.

### Type Asserts

AssertionUtils:assertType

AssertionUtils:assertTypes

----
AssertionUtils:safeAssertType

AssertionUtils:safeAssertTypes

----
AssertionUtils:safeWarnAssertType

AssertionUtils:safeWarnAssertTypes

----
### Class Asserts

AssertionUtils:assertClass

AssertionUtils:assertClasses

----
AssertionUtils:safeAssertClass

AssertionUtils:safeAssertClasses

----
AssertionUtils:safeWarnAssertClass

AssertionUtils:safeWarnAssertClasses
