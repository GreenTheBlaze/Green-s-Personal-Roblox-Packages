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
