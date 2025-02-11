# Sorted List

bio book is reference for comments

----
## Miscellanious

InstanceUtils:createInstance

InstanceUtils:createInstances

----
InstanceUtils:setInstanceProperties

InstanceUtils:setInstancesProperties

----
InstanceUtils:cloneAndSetProperties

InstanceUtils:clonesAndSetProperties

----
## Get

InstanceUtils:getSiblings(child: Instance): {Instance}

InstanceUtils:getAncestors(descendant: Instance): {Instance}

----
InstanceUtils:getChildrenOfName(parent: Instance, name: string): {Instance}

InstanceUtils:getSiblingsOfName(child: Instance, name: string): {Instance}

InstanceUtils:getDescendantsOfName(ancestor: Instance, name: string): {Instance}

InstanceUtils:getAncestorsOfName(descendant: Instance, name: string): {Instance}

----
InstanceUtils:getChildrenOfNameRange

InstanceUtils:getSiblingsOfNameRange

InstanceUtils:getDescendantsOfNameRange

InstanceUtils:getAncestorsOfNameRange

----
InstanceUtils:getChildrenOfClass

InstanceUtils:getSiblingsOfClass

InstanceUtils:getDescendantsOfClass

InstanceUtils:getAncestorsOfClass

----
InstanceUtils:getChildrenOfClassRange

InstanceUtils:getSiblingsOfClassRange

InstanceUtils:getDescendantsOfClassRange

InstanceUtils:getAncestorsOfClassRange

----
InstanceUtils:getChildrenOfNameAndClass

InstanceUtils:getSiblingsOfNameAndClass

InstanceUtils:getDescendantsOfNameAndClass

InstanceUtils:getAncestorsOfNameAndClass

----
InstanceUtils:getChildrenOfNameRangeAndClassRange

InstanceUtils:getSiblingsOfNameRangeAndClassRange

InstanceUtils:getDescendantsOfNameRangeAndClassRange

InstanceUtils:getAncestorsOfNameRangeAndClassRange

----
InstanceUtils:getChildrenOfNameRangeAndClassRange

InstanceUtils:getSiblingsOfNameRangeAndClassRange

InstanceUtils:getDescendantsOfNameRangeAndClassRange

InstanceUtils:getAncestorsOfNameRangeAndClassRange

----
InstanceUtils:getChildrenOfProperties

InstanceUtils:getSiblingsOfProperties

InstanceUtils:getDescendantsOfProperties

InstanceUtils:getAncestorsOfProperties

----
InstanceUtils:getChildrenOfPropertiesRange

InstanceUtils:getSiblingsOfPropertiesRange

InstanceUtils:getDescendantsOfPropertiesRange

InstanceUtils:getAncestorsOfPropertiesRange

----
InstanceUtils:getInstancesFromTable

InstanceUtils:getInstancesOfNameFromTable(parent: Instance, name: string): {Instance}

InstanceUtils:getInstancesOfNameRangeFromTable

InstanceUtils:getInstancesOfClassFromTable

InstanceUtils:getInstancesOfClassRangeFromTable

InstanceUtils:getInstancesOfNameAndClassFromTable

InstanceUtils:getInstancesOfNameRangeAndClassRangeFromTable

InstanceUtils:getInstancesOfPropertiesFromTable

InstanceUtils:getInstancesOfPropertiesRangeFromTable

InstanceUtils:getInstancesOfPropertiesRangeFromTable

----
## Clear
**Notes:**
* ClearAncestors ***ARE*** allowed

InstanceUtils:clearAllSiblings

----
InstanceUtils:clearChildrenOfName(parent: Instance, name: string): {Instance}

InstanceUtils:clearSiblingsOfName(child: Instance, name: string): {Instance}

InstanceUtils:clearDescendantsOfName(ancestor: Instance, name: string): {Instance}

InstanceUtils:clearAncestorsOfName(ancestor: Instance, name: string): {Instance}

----
InstanceUtils:clearChildrenOfNameRange

InstanceUtils:clearSiblingsOfNameRange

InstanceUtils:clearDescendantsOfNameRange

InstanceUtils:clearAncestorsOfNameRange

----
InstanceUtils:clearChildrenOfClass

InstanceUtils:clearSiblingsOfClass

InstanceUtils:clearDescendantsOfClass

InstanceUtils:clearAncestorsOfClass

----
InstanceUtils:clearChildrenOfClassRange

InstanceUtils:clearSiblingsOfClassRange

InstanceUtils:clearDescendantsOfClassRange

InstanceUtils:clearAncestorsOfClassRange

----
InstanceUtils:clearChildrenOfNameAndClass

InstanceUtils:clearSiblingsOfNameAndClass

InstanceUtils:clearDescendantsOfNameAndClass

InstanceUtils:clearAncestorsOfNameAndClass

----
InstanceUtils:clearChildrenOfNameRangeAndClassRange

InstanceUtils:clearSiblingsOfNameRangeAndClassRange

InstanceUtils:clearDescendantsOfNameRangeAndClassRange

InstanceUtils:clearAncestorsOfNameRangeAndClassRange

----
InstanceUtils:clearChildrenOfNameRangeAndClassRange

InstanceUtils:clearSiblingsOfNameRangeAndClassRange

InstanceUtils:clearDescendantsOfNameRangeAndClassRange

InstanceUtils:clearAncestorsOfNameRangeAndClassRange

----
InstanceUtils:clearChildrenOfProperties

InstanceUtils:clearSiblingsOfProperties

InstanceUtils:clearDescendantsOfProperties

InstanceUtils:clearAncestorsOfProperties

----
InstanceUtils:clearChildrenOfPropertiesRange

InstanceUtils:clearSiblingsOfPropertiesRange

InstanceUtils:clearDescendantsOfPropertiesRange

InstanceUtils:clearAncestorsOfPropertiesRange

----
InstanceUtils:clearInstancesFromTable

InstanceUtils:clearInstancesOfNameFromTable(parent: Instance, name: string): {Instance}

InstanceUtils:clearInstancesOfNameRangeFromTable

InstanceUtils:clearInstancesOfClassFromTable

InstanceUtils:clearInstancesOfClassRangeFromTable

InstanceUtils:clearInstancesOfNameAndClassFromTable

InstanceUtils:clearInstancesOfNameRangeAndClassRangeFromTable

InstanceUtils:clearInstancesOfPropertiesFromTable

InstanceUtils:clearInstancesOfPropertiesRangeFromTable

InstanceUtils:clearInstancesOfPropertiesRangeFromTable

----
## WaitFor

InstanceUtils:waitForSibling

InstanceUtils:waitForDescendant

InstanceUtils:waitForAncestor

----
InstanceUtils:waitForChildren

InstanceUtils:waitForSiblings

InstanceUtils:waitForDescendants

InstanceUtils:waitForAncestors

----
InstanceUtils:waitForChildOfNameRange

InstanceUtils:waitForSiblingOfNameRange

InstanceUtils:waitForDescendantOfNameRange

InstanceUtils:waitForAncestorOfNameRange

----
InstanceUtils:waitForChildrenOfNameRanges

InstanceUtils:waitForSiblingsOfNameRanges

InstanceUtils:waitForDescendantsOfNameRanges

InstanceUtils:waitForAncestorsOfNameRanges

----
InstanceUtils:waitForChildOfClass

InstanceUtils:waitForSiblingOfClass

InstanceUtils:waitForDescendantOfClass

InstanceUtils:waitForAncestorOfClass

----
InstanceUtils:waitForChildrenOfClasses

InstanceUtils:waitForSiblingsOfClasses

InstanceUtils:waitForDescendantsOfClasses

InstanceUtils:waitForAncestorsOfClasses

----
InstanceUtils:waitForChildOfClassRange

InstanceUtils:waitForSiblingOfClassRange

InstanceUtils:waitForDescendantOfClassRange

InstanceUtils:waitForAncestorOfClassRange

----
InstanceUtils:waitForChildrenOfClassRanges

InstanceUtils:waitForSiblingsOfClassRanges

InstanceUtils:waitForDescendantsOfClassRanges

InstanceUtils:waitForAncestorsOfClassRanges

----
InstanceUtils:waitForChildOfNameAndClass

InstanceUtils:waitForSiblingOfNameAndClass

InstanceUtils:waitForDescendantOfNameAndClass

InstanceUtils:waitForAncestorOfNameAndClass

----
InstanceUtils:waitForChildrenOfNamesAndClasses

InstanceUtils:waitForSiblingsOfNamesAndClasses

InstanceUtils:waitForDescendantsOfNamesAndClasses

InstanceUtils:waitForAncestorsOfNamesAndClasses

----
InstanceUtils:waitForChildOfNameRangeAndClassRange

InstanceUtils:waitForSiblingOfNameRangeAndClassRange

InstanceUtils:waitForDescendantOfNameRangeAndClassRange

InstanceUtils:waitForAncestorOfNameRangeAndClassRange

----
InstanceUtils:waitForChildrenOfNameRangesAndClassRanges

InstanceUtils:waitForSiblingsOfNameRangesAndClassRanges

InstanceUtils:waitForDescendantsOfNameRangesAndClassRanges

InstanceUtils:waitForAncestorsOfNameRangesAndClassRanges

----
InstanceUtils:waitForChildOfProperties

InstanceUtils:waitForSiblingOfProperties

InstanceUtils:waitForDescendantOfProperties

InstanceUtils:waitForAncestorOfProperties

----
InstanceUtils:waitForChildrenOfProperties

InstanceUtils:waitForSiblingsOfProperties

InstanceUtils:waitForDescendantsOfProperties

InstanceUtils:waitForAncestorsOfProperties

----
InstanceUtils:waitForChildOfPropertiesRange

InstanceUtils:waitForSiblingOfPropertiesRange

InstanceUtils:waitForDescendantOfPropertiesRange

InstanceUtils:waitForAncestorOfPropertiesRange

----
InstanceUtils:waitForChildrenOfPropertiesRanges

InstanceUtils:waitForSiblingsOfPropertiesRanges

InstanceUtils:waitForDescendantsOfPropertiesRanges

InstanceUtils:waitForAncestorsOfPropertiesRanges

----
InstanceUtils:waitForChildWhichHasProperties

InstanceUtils:waitForSiblingWhichHasProperties

InstanceUtils:waitForDescendantWhichHasProperties

InstanceUtils:waitForAncestorWhichHasProperties

----
InstanceUtils:waitForChildrenWhichHaveProperties

InstanceUtils:waitForSiblingsWhichHaveProperties

InstanceUtils:waitForDescendantsWhichHaveProperties

InstanceUtils:waitForAncestorsWhichHaveProperties

----
InstanceUtils:waitForInstanceFromTable

InstanceUtils:waitForInstancesFromTable

----
InstanceUtils:waitForInstanceOfClassFromTable

InstanceUtils:waitForInstancesOfClassesFromTable

----
InstanceUtils:waitForInstanceOfClassRangeFromTable

InstanceUtils:waitForInstancesOfClassRangesFromTable

----
InstanceUtils:waitForInstanceOfNameAndClassFromTable

InstanceUtils:waitForInstancesOfNamesAndClassesFromTable

----
InstanceUtils:waitForInstanceOfNameRangeAndClassRangeFromTable

InstanceUtils:waitForInstancesOfNameRangesAndClassRangesFromTable

----
InstanceUtils:waitForInstanceOfPropertiesFromTable

InstanceUtils:waitForInstancesOfPropertiesFromTable

----
InstanceUtils:waitForInstanceOfPropertiesRangeFromTable

InstanceUtils:waitForInstancesOfPropertiesRangesFromTable

----
InstanceUtils:waitForInstanceWhichHasPropertiesFromTable

InstanceUtils:waitForInstancesWhichHavePropertiesFromTable

----
InstanceUtils:waitForInstancesInPath

----
InstanceUtils:waitForInstancesOfNamesInPath

InstanceUtils:waitForInstancesOfNameRangesInPath

----
InstanceUtils:waitForInstancesOfClassesInPath

InstanceUtils:waitForInstancesOfClassRangesInPath

----
InstanceUtils:waitForInstancesOfNamesAndClassesInPath

InstanceUtils:waitForInstancesOfNameRangesAndClassRangesInPath

----
## FindFirst

InstanceUtils:findFirstSibling

InstanceUtils:findFirstDescendant

----
InstanceUtils:findFirstChildren

InstanceUtils:findFirstSiblings

InstanceUtils:findFirstDescendants

InstanceUtils:findFirstAncestors

----
InstanceUtils:findFirstChildOfNameRange

InstanceUtils:findFirstSiblingOfNameRange

InstanceUtils:findFirstDescendantOfNameRange

InstanceUtils:findFirstAncestorOfNameRange

----
InstanceUtils:findFirstChildrenOfNameRanges

InstanceUtils:findFirstSiblingsOfNameRanges

InstanceUtils:findFirstDescendantsOfNameRanges

InstanceUtils:findFirstAncestorsOfNameRanges

----
InstanceUtils:findFirstSiblingOfClass

InstanceUtils:findFirstDescendantOfClass

----
InstanceUtils:findFirstChildrenOfClasses

InstanceUtils:findFirstSiblingsOfClasses

InstanceUtils:findFirstDescendantsOfClasses

InstanceUtils:findFirstAncestorsOfClasses

----
InstanceUtils:findFirstChildOfClassRange

InstanceUtils:findFirstSiblingOfClassRange

InstanceUtils:findFirstDescendantOfClassRange

InstanceUtils:findFirstAncestorOfClassRange

----
InstanceUtils:findFirstChildrenOfClassRanges

InstanceUtils:findFirstSiblingsOfClassRanges

InstanceUtils:findFirstDescendantsOfClassRanges

InstanceUtils:findFirstAncestorsOfClassRanges

----
InstanceUtils:findFirstChildOfNameAndClass

InstanceUtils:findFirstSiblingOfNameAndClass

InstanceUtils:findFirstDescendantOfNameAndClass

InstanceUtils:findFirstAncestorOfNameAndClass

----
InstanceUtils:findFirstChildrenOfNamesAndClasses

InstanceUtils:findFirstSiblingsOfNamesAndClasses

InstanceUtils:findFirstDescendantsOfNamesAndClasses

InstanceUtils:findFirstAncestorsOfNamesAndClasses

----
InstanceUtils:findFirstChildOfNameRangeAndClassRange

InstanceUtils:findFirstSiblingOfNameRangeAndClassRange

InstanceUtils:findFirstDescendantOfNameRangeAndClassRange

InstanceUtils:findFirstAncestorOfNameRangeAndClassRange

----
InstanceUtils:findFirstChildrenOfNameRangesAndClassRanges

InstanceUtils:findFirstSiblingsOfNameRangesAndClassRanges

InstanceUtils:findFirstDescendantsOfNameRangesAndClassRanges

InstanceUtils:findFirstAncestorsOfNameRangesAndClassRanges

----
InstanceUtils:findFirstChildOfProperties

InstanceUtils:findFirstSiblingOfProperties

InstanceUtils:findFirstDescendantOfProperties

InstanceUtils:findFirstAncestorOfProperties

----
InstanceUtils:findFirstChildrenOfProperties

InstanceUtils:findFirstSiblingsOfProperties

InstanceUtils:findFirstDescendantsOfProperties

InstanceUtils:findFirstAncestorsOfProperties

----
InstanceUtils:findFirstChildOfPropertiesRange

InstanceUtils:findFirstSiblingOfPropertiesRange

InstanceUtils:findFirstDescendantOfPropertiesRange

InstanceUtils:findFirstAncestorOfPropertiesRange

----
InstanceUtils:findFirstChildrenOfPropertiesRanges

InstanceUtils:findFirstSiblingsOfPropertiesRanges

InstanceUtils:findFirstDescendantsOfPropertiesRanges

InstanceUtils:findFirstAncestorsOfPropertiesRanges

----
InstanceUtils:findFirstChildWhichHasProperties

InstanceUtils:findFirstSiblingWhichHasProperties

InstanceUtils:findFirstDescendantWhichHasProperties

InstanceUtils:findFirstAncestorWhichHasProperties

----
InstanceUtils:findFirstChildrenWhichHaveProperties

InstanceUtils:findFirstSiblingsWhichHaveProperties

InstanceUtils:findFirstDescendantsWhichHaveProperties

InstanceUtils:findFirstAncestorsWhichHaveProperties

----
InstanceUtils:findFirstInstanceFromTable

InstanceUtils:findFirstInstancesFromTable

----
InstanceUtils:findFirstInstanceOfClassFromTable

InstanceUtils:findFirstInstancesOfClassesFromTable

----
InstanceUtils:findFirstInstanceOfClassRangeFromTable

InstanceUtils:findFirstInstancesOfClassRangesFromTable

----
InstanceUtils:findFirstInstanceOfNameAndClassFromTable

InstanceUtils:findFirstInstancesOfNamesAndClassesFromTable

----
InstanceUtils:findFirstInstanceOfNameRangeAndClassRangeFromTable

InstanceUtils:findFirstInstancesOfNameRangesAndClassRangesFromTable

----
InstanceUtils:findFirstInstanceOfPropertiesFromTable

InstanceUtils:findFirstInstancesOfPropertiesFromTable

----
InstanceUtils:findFirstInstanceOfPropertiesRangeFromTable

InstanceUtils:findFirstInstancesOfPropertiesRangesFromTable

----
InstanceUtils:findFirstInstanceWhichHasPropertiesFromTable

InstanceUtils:findFirstInstancesWhichHavePropertiesFromTable

----

----- ABOVE NEEDS TO BE FINISHED
----

## Unsorted Stage2

InstanceUtils:getChildrenOfName(parent: Instance, name: string): {Instance}

InstanceUtils:getSiblingsOfName(child: Instance, name: string): {Instance}

InstanceUtils:getDescendantsOfName(ancestor: Instance, name: string): {Instance}

InstanceUtils:getAncestorsOfName(descendant: Instance, name: string): {Instance}

function InstanceUtils:getChildrenOfNameRange(parent: Instance, NameRange: {string}): {Instance}

function InstanceUtils:getSiblingsOfNameRange(child: Instance, NameRange: {string}): {Instance}

function InstanceUtils:getDescendantsOfNameRange(ancestor: Instance, NameRange: {string}): {Instance}
	assert(typeof(ancestor) == "Instance", "Invalid argument #1 to 'getDescendantsOfNameRange' (Instance expected)")
	assert(typeof(NameRange) == "table", "Invalid argument #2 to 'getDescendantsOfNameRange' (table expected)")

	local foundDescendants: {Instance} = {}

	for _, name: string in NameRange do
		for _, descendant: Instance in InstanceUtils:getDescendantsOfName(ancestor, name) do
			table.insert(foundDescendants, descendant)
		end
	end

	return foundDescendants
end

function InstanceUtils:getAncestorsOfNameRange(descendant: Instance, NameRange: {string}): {Instance}
	assert(typeof(descendant) == "Instance", "Invalid argument #1 to 'getAncestorsOfNameRange' (Instance expected)")
	assert(descendant.Parent ~= nil, "Invalid argument #1 to 'getAncestorsOfNameRange' (Instance parent is nil)")
	assert(typeof(NameRange) == "table", "Invalid argument #2 to 'getAncestorsOfNameRange' (table expected)")

	local foundAncestors: {Instance} = {}

	for _, name: string in NameRange do
		for _, ancestor: Instance in InstanceUtils:getAncestorsOfName(descendant, name) do
			table.insert(foundAncestors, ancestor)
		end
	end

	return foundAncestors
end

--

function InstanceUtils:getChildrenOfClass(parent: Instance, className: string): {Instance}
	assert(typeof(parent) == "Instance", "Invalid argument #1 to 'getChildrenOfClass' (Instance expected)")
	assert(typeof(className) == "string", "Invalid argument #2 to 'getChildrenOfClass' (string expected)")

	local foundChildren: {Instance} = {}

	for _, child: Instance in parent:GetChildren() do
		if child.ClassName == className then
			table.insert(foundChildren, child)
		end
	end

	return foundChildren
end

function InstanceUtils:getSiblingsOfClass(child: Instance, className: string): {Instance}
	assert(typeof(child) == "Instance", "Invalid argument #1 to 'getSiblingsOfClass' (Instance expected)")
	assert(child.Parent ~= nil, "Invalid argument #1 to 'getSiblingsOfClass' (Instance parent is nil)")
	assert(typeof(className) == "string", "Invalid argument #2 to 'getSiblingsOfClass' (string expected)")

	local foundSiblings: {Instance} = {}

	for _, sibling: Instance in InstanceUtils:getSiblings(child) do
		if sibling.ClassName == className then
			table.insert(foundSiblings, sibling)
		end
	end

	return foundSiblings
end

function InstanceUtils:getDescendantsOfClass(ancestor: Instance, className: string): {Instance}
	assert(typeof(ancestor) == "Instance", "Invalid argument #1 to 'getDescendantsOfClass' (Instance expected)")
	assert(typeof(className) == "string", "Invalid argument #2 to 'getDescendantsOfClass' (string expected)")

	local foundDescendants: {Instance} = {}

	for _, descendant: Instance in ancestor:GetDescendants() do
		if descendant.ClassName == className then
			table.insert(foundDescendants, descendant)
		end
	end

	return foundDescendants
end

function InstanceUtils:getAncestorsOfClass(descendant: Instance, className: string): {Instance}
	assert(typeof(descendant) == "Instance", "Invalid argument #1 to 'getAncestorsOfClass' (Instance expected)")
	assert(descendant.Parent ~= nil, "Invalid argument #1 to 'getAncestorsOfClass' (Instance parent is nil)")
	assert(typeof(className) == "string", "Invalid argument #2 to 'getAncestorsOfClass' (string expected)")

	local foundAncestors: {Instance} = {}

	for _, ancestor: Instance in InstanceUtils:getAncestors(descendant) do
		if ancestor.ClassName == className then
			table.insert(foundAncestors, ancestor)
		end
	end

	return foundAncestors
end

--

function InstanceUtils:getChildrenOfClassRange(parent: Instance, classNameRange: {string}): {Instance}
	assert(typeof(parent) == "Instance", "Invalid argument #1 to 'getChildrenOfClassRange' (Instance expected)")
	assert(typeof(classNameRange) == "table", "Invalid argument #2 to 'getChildrenOfClassRange' (table expected)")

	local foundChildren: {Instance} = {}

	for _, className: string in classNameRange do
		for _, child: Instance in InstanceUtils:getChildrenOfClass(parent, className) do
			table.insert(foundChildren, child)
		end
	end

	return foundChildren
end

function InstanceUtils:getSiblingsOfClassRange(child: Instance, classNameRange: {string}): {Instance}
	assert(typeof(child) == "Instance", "Invalid argument #1 to 'getSiblingsOfClassRange' (Instance expected)")
	assert(child.Parent ~= nil, "Invalid argument #1 to 'getSiblingsOfClassRange' (Instance parent is nil)")
	assert(typeof(classNameRange) == "table", "Invalid argument #2 to 'getSiblingsOfClassRange' (table expected)")

	local foundSiblings: {Instance} = {}

	for _, className: string in classNameRange do
		for _, sibling: Instance in InstanceUtils:getSiblingsOfClass(child, className) do
			table.insert(foundSiblings, sibling)
		end
	end

	return foundSiblings
end

function InstanceUtils:getDescendantsOfClassRange(ancestor: Instance, classNameRange: {string}): {Instance}
	assert(typeof(ancestor) == "Instance", "Invalid argument #1 to 'getDescendantsOfClassRange' (Instance expected)")
	assert(typeof(classNameRange) == "table", "Invalid argument #2 to 'getDescendantsOfClassRange' (table expected)")

	local foundDescendants: {Instance} = {}

	for _, className: string in classNameRange do
		for _, descendant: Instance in InstanceUtils:getDescendantsOfClass(ancestor, className) do
			table.insert(foundDescendants, descendant)
		end
	end

	return foundDescendants
end

function InstanceUtils:getAncestorsOfClassRange(descendant: Instance, classNameRange: {string}): {Instance}
	assert(typeof(descendant) == "Instance", "Invalid argument #1 to 'getAncestorsOfClassRange' (Instance expected)")
	assert(descendant.Parent ~= nil, "Invalid argument #1 to 'getAncestorsOfClassRange' (Instance parent is nil)")
	assert(typeof(classNameRange) == "table", "Invalid argument #2 to 'getAncestorsOfClassRange' (table expected)")

	local foundAncestors: {Instance} = {}

	for _, className: string in classNameRange do
		for _, ancestor: Instance in InstanceUtils:getAncestorsOfClass(descendant, className) do
			table.insert(foundAncestors, descendant)
		end
	end

	return foundAncestors
end

--

function InstanceUtils:getChildrenOfNameAndClass(child: Instance, siblingName: string, className: string): {Instance?}

end

function InstanceUtils:getSiblingsOfNameAndClass(child: Instance, siblingName: string, className: string): {Instance?}

end

function InstanceUtils:getDescendantsOfNameAndClass(child: Instance, siblingName: string, className: string): {Instance?}

end

function InstanceUtils:getAncestorsOfNameAndClass(child: Instance, siblingName: string, className: string): {Instance?}

end

--

function InstanceUtils:getChildrenOfRangeNamesAndClasses(child: Instance, siblingNames: {string}, classNames: {string}): {Instance?}

end

function InstanceUtils:getSiblingsOfRangeNamesAndClasses(child: Instance, siblingNames: {string}, classNames: {string}): {Instance?}

end

function InstanceUtils:getDescendantsOfRangeNamesAndClasses(child: Instance, siblingNames: {string}, classNames: {string}): {Instance?}

end

function InstanceUtils:getAncestorsOfRangeNamesAndClasses(child: Instance, siblingNames: {string}, classNames: {string}): {Instance?}

end

--

function InstanceUtils:getChildrenOfNameRangeAndClass(child: Instance, siblingNames: {string}, className: string): {Instance?}

end

function InstanceUtils:getSiblingsOfNameRangeAndClass(child: Instance, siblingNames: {string}, className: string): {Instance?}

end

function InstanceUtils:getDescendantsOfNameRangeAndClass(child: Instance, siblingNames: {string}, className: string): {Instance?}

end

function InstanceUtils:getAncestorsOfNameRangeAndClass(child: Instance, siblingNames: {string}, className: string): {Instance?}

end

--

function InstanceUtils:getChildrenOfNameAndClassRange(child: Instance, siblingName: string, classNames: {string}): {Instance?}

end

function InstanceUtils:getSiblingsOfNameAndClassRange(child: Instance, siblingName: string, classNames: {string}): {Instance?}

end

function InstanceUtils:getDescendantsOfNameAndClassRange(child: Instance, siblingName: string, classNames: {string}): {Instance?}

end

function InstanceUtils:getAncestorsOfNameAndClassRange(child: Instance, siblingName: string, classNames: {string}): {Instance?}

end

----
# Dump (Unsorted)

InstanceUtils:create(className: string?, propertiesTable: StringKeyDictionary<any>): Instance

InstanceUtils:cloneWithNewProperties(cloneInstance: Instance, propertiesTable: StringKeyDictionary<any>): Instance

InstanceUtils:isAValidPropertyOfInstance(checkInstance: Instance, property: string): (boolean, string)

InstanceUtils:hasProperties(searchInstance: Instance, propertiesTable: StringKeyDictionary<any>): boolean

InstanceUtils:hasPropertiesDebug(searchInstance: Instance, propertiesTable: StringKeyDictionary<any>): (boolean, Array<string>)

InstanceUtils:hasPropertyOfRange(searchInstance: Instance, propertyRangeKey: string, propertyRangeTable: Array<any>): boolean

InstanceUtils:hasPropertiesOfRanges(searchInstance: Instance, propertiesRangesTable: StringKeyDictionary<any>): boolean

InstanceUtils:clearAllSiblings(child: Instance)

InstanceUtils:clearAllDescendants(ancestor: Instance)

InstanceUtils:clearChildrenOfName(parent: Instance, name: string): {Instance?}

InstanceUtils:clearSiblingsOfName(child: Instance, name: string): {Instance?}

InstanceUtils:clearDescendantsOfName(ancestor: Instance, name: string): {Instance?}

--

InstanceUtils:clearChildrenOfNameRange(parent: Instance, names: {string}): {Instance?}

InstanceUtils:clearSiblingsOfNameRange(child: Instance, names: {string}): {Instance?}

InstanceUtils:clearDescendantsOfNameRange(child: Instance, names: {string}): {Instance?}

--

function InstanceUtils:clearChildrenOfClass(child: Instance, className: string): {Instance?}

function InstanceUtils:clearSiblingsOfClass(child: Instance, className: string): {Instance?}

function InstanceUtils:clearDescendantsOfClass(child: Instance, className: string): {Instance?}

--

function InstanceUtils:clearChildrenOfClassRange(child: Instance, classNames: {string}): {Instance?}

function InstanceUtils:clearSiblingsOfClassRange(child: Instance, classNames: {string}): {Instance?}

function InstanceUtils:clearDescendantsOfClassRange(child: Instance, classNames: {string}): {Instance?}

--

function InstanceUtils:clearChildrenOfNameAndClass(child: Instance, siblingName: string, className: string): {Instance?}

end

function InstanceUtils:clearSiblingsOfNameAndClass(child: Instance, siblingName: string, className: string): {Instance?}

end

function InstanceUtils:clearDescendantsOfNameAndClass(child: Instance, siblingName: string, className: string): {Instance?}

end

--

function InstanceUtils:clearChildrenOfRangeNamesAndClasses(child: Instance, siblingNames: {string}, classNames: {string}): {Instance?}

end

function InstanceUtils:clearSiblingsOfRangeNamesAndClasses(child: Instance, siblingNames: {string}, classNames: {string}): {Instance?}

end

function InstanceUtils:clearDescendantsOfRangeNamesAndClasses(child: Instance, siblingNames: {string}, classNames: {string}): {Instance?}

end

--

function InstanceUtils:clearChildrenOfNameRangeAndClass(child: Instance, siblingNames: {string}, className: string): {Instance?}

end

function InstanceUtils:clearSiblingsOfNameRangeAndClass(child: Instance, siblingNames: {string}, className: string): {Instance?}

end

function InstanceUtils:clearDescendantsOfNameRangeAndClass(child: Instance, siblingNames: {string}, className: string): {Instance?}

end

--

function InstanceUtils:clearChildrenOfNameAndClassRange(child: Instance, siblingName: string, classNames: {string}): {Instance?}

end

function InstanceUtils:clearSiblingsOfNameAndClassRange(child: Instance, siblingName: string, classNames: {string}): {Instance?}

end

function InstanceUtils:clearDescendantsOfNameAndClassRange(child: Instance, siblingName: string, classNames: {string}): {Instance?}

end

--

function InstanceUtils:clearChildrenThatHavePropertyKey(child: Instance, propertyKey: string): {Instance?}

end

function InstanceUtils:clearSiblingsThatHavePropertyKey(child: Instance, propertyKey: string): {Instance?}

end

function InstanceUtils:clearDescendantsThatHavePropertyKey(child: Instance, propertyKey: string): {Instance?}

end

--

function InstanceUtils:clearChildrenThatHavePropertyKeys(child: Instance, propertyKeys: {string}): {Instance?}

end

function InstanceUtils:clearSiblingsThatHavePropertyKeys(child: Instance, propertyKeys: {string}): {Instance?}

end

function InstanceUtils:clearDescendantsThatHavePropertyKeys(child: Instance, propertyKeys: {string}): {Instance?}

end

--

function InstanceUtils:clearChildrenOfProperties(child: Instance, propertiesTable: StringKeyDictionary<any>): {Instance?}

end

function InstanceUtils:clearSiblingsOfProperties(child: Instance, propertiesTable: StringKeyDictionary<any>): {Instance?}

end

function InstanceUtils:clearDescendantsOfProperties(child: Instance, propertiesTable: StringKeyDictionary<any>): {Instance?}

end

--

function InstanceUtils:clearChildrenOfExactProperties(child: Instance, propertiesTable: StringKeyDictionary<any>): {Instance?}

end

function InstanceUtils:clearSiblingsOfExactProperties(child: Instance, propertiesTable: StringKeyDictionary<any>): {Instance?}

end

function InstanceUtils:clearDescendantsOfExactProperties(child: Instance, propertiesTable: StringKeyDictionary<any>): {Instance?}

end

--
--
--

function InstanceUtils:getInstancesFromTableOfName(searchTable: {Instance}, name: string): {Instance}
end

function InstanceUtils:getInstancesFromTableOfNameRange(searchTable: {Instance}, NameRange: {string}): {Instance}
	assert(typeof(searchTable) == "table", "Invalid argument #1 to 'getInstancesFromTableOfNameRange' (table expected)")
	assert(typeof(NameRange) == "table", "Invalid argument #2 to 'getInstancesFromTableOfNameRange' (table expected)")

	local foundInstances: {Instance} = {}

	for _, name: string in NameRange do
		for _, instance: Instance in InstanceUtils:getInstancesFromTableOfName(searchTable, name) do
			table.insert(foundInstances, instance)
		end
	end

	return foundInstances
end

function InstanceUtils:getInstancesFromTableOfClass(searchTable: {Instance}, className: string): {Instance}
	assert(typeof(searchTable) == "table", "Invalid argument #1 to 'getInstancesFromTableOfClass' (table expected)")
	assert(typeof(className) == "string", "Invalid argument #2 to 'getInstancesFromTableOfClass' (string expected)")

	local foundInstances: {Instance} = {}

	for _, instance: Instance in searchTable do
		if instance.ClassName == className then
			table.insert(foundInstances, instance)
		end
	end

	return foundInstances
end

function InstanceUtils:getInstancesFromTableOfClassRange(searchTable: {Instance}, classNameRange: {string}): {Instance}
	assert(typeof(searchTable) == "table", "Invalid argument #1 to 'getInstancesFromTableOfClassRange' (table expected)")
	assert(typeof(classNameRange) == "table", "Invalid argument #2 to 'getInstancesFromTableOfClassRange' (table expected)")

	local foundInstances: {Instance} = {}

	for _, className: string in classNameRange do
		for _, instance: Instance in InstanceUtils:getInstancesFromTableOfClass(searchTable, className) do
			table.insert(foundInstances, instance)
		end
	end

	return foundInstances
end

function InstanceUtils:getInstancesFromTableOfProperties(searchTable: {Instance}, propertiesTable: StringKeyDictionary<any>): {Instance}
	assert(typeof(searchTable) == "table", "Invalid argument #1 to 'getInstancesFromTableOfProperties' (table expected)")
	assert(typeof(propertiesTable) == "table", "Invalid argument #2 to 'getInstancesFromTableOfProperties' (dictionary expected)")

	local foundInstances: {Instance} = {}

	for _, instance: Instance in searchTable do
		local childHasProperties: boolean = InstanceUtils:hasProperties(instance, propertiesTable)

		if childHasProperties == true then
			table.insert(foundInstances, instance)
		end
	end

	return foundInstances
end

--

function InstanceUtils:getSiblings(child: Instance): {Instance}
	assert(typeof(child) == "Instance", "Invalid argument #1 to 'getSiblings' (Instance expected)")
	assert(child.Parent ~= nil, "Invalid argument #1 to 'getSiblings' (Instance parent is nil)")

	local foundSiblings: {Instance} = {}

	for _, sibling: Instance in child.Parent:GetChildren() do
		if sibling == child then
			continue
		end

		table.insert(foundSiblings, sibling)
	end

	return foundSiblings
end

function InstanceUtils:getAncestors(descendant: Instance): {Instance}
	assert(typeof(descendant) == "Instance", "Invalid argument #1 to 'getAncestors' (Instance expected)")
	assert(descendant.Parent ~= nil, "Invalid argument #1 to 'getAncestors' (Instance parent is nil)")

	local foundAncestors: {Instance} = {}

	local currentAncestor: Instance? = descendant.Parent

	while currentAncestor ~= nil do
		table.insert(foundAncestors, currentAncestor)
		currentAncestor = currentAncestor.Parent
	end

	return foundAncestors
end

--

function InstanceUtils:getChildrenOfName(parent: Instance, name: string): {Instance}
	assert(typeof(parent) == "Instance", "Invalid argument #1 to 'getChildrenOfName' (Instance expected)")
	assert(typeof(name) == "string", "Invalid argument #2 to 'getChildrenOfName' (string expected)")

	local foundChildren: {Instance} = InstanceUtils:getInstancesFromTableOfName(parent:GetChildren(), name)

	return foundChildren
end

--[[
	Old:
	
	function InstanceUtils:getChildrenOfName(parent: Instance, name: string): {Instance}
		assert(typeof(parent) == "Instance", "Invalid argument #1 to 'getChildrenOfName' (Instance expected)")
		assert(typeof(name) == "string", "Invalid argument #2 to 'getChildrenOfName' (string expected)")

		local foundChildren: {Instance} = {}

		for _, child: Instance in parent:GetChildren() do
			if child.Name == name then
				table.insert(foundChildren, child)
			end
		end

		return foundChildren
	end
]]

function InstanceUtils:getSiblingsOfName(child: Instance, name: string): {Instance}
	assert(typeof(child) == "Instance", "Invalid argument #1 to 'getSiblingsOfName' (Instance expected)")
	assert(child.Parent ~= nil, "Invalid argument #1 to 'getSiblingsOfName' (Instance parent is nil)")
	assert(typeof(name) == "string", "Invalid argument #2 to 'getSiblingsOfName' (string expected)")

	local foundSiblings: {Instance} = InstanceUtils:getInstancesFromTableOfName(InstanceUtils:getSiblings(child), name)

	return foundSiblings
end

--TODO: finish these off following the above format of getInstancesFromTable
function InstanceUtils:getDescendantsOfName(ancestor: Instance, name: string): {Instance}
	assert(typeof(ancestor) == "Instance", "Invalid argument #1 to 'getDescendantsOfName' (Instance expected)")
	assert(typeof(name) == "string", "Invalid argument #2 to 'getDescendantsOfName' (string expected)")

	local foundDescendants: {Instance} = InstanceUtils:getInstancesFromTableOfName(ancestor:GetDescendants(), name)

	return foundDescendants
end

function InstanceUtils:getAncestorsOfName(descendant: Instance, name: string): {Instance}
	assert(typeof(descendant) == "Instance", "Invalid argument #1 to 'getAncestorsOfName' (Instance expected)")
	assert(descendant.Parent ~= nil, "Invalid argument #1 to 'getAncestorsOfName' (Instance parent is nil)")
	assert(typeof(name) == "string", "Invalid argument #2 to 'getAncestorsOfName' (string expected)")

	local foundAncestors: {Instance} = InstanceUtils:getInstancesFromTableOfName(InstanceUtils:getAncestors(descendant), name)

	return foundAncestors
end

--

function InstanceUtils:getChildrenOfNameRange(parent: Instance, NameRange: {string}): {Instance}
	assert(typeof(parent) == "Instance", "Invalid argument #1 to 'getChildrenOfNameRange' (Instance expected)")
	assert(typeof(NameRange) == "table", "Invalid argument #2 to 'getChildrenOfNameRange' (table expected)")

	local foundChildren: {Instance} = {}

	for _, name: string in NameRange do
		for _, child: Instance in InstanceUtils:getChildrenOfName(parent, name) do
			table.insert(foundChildren, child)
		end
	end

	return foundChildren
end

function InstanceUtils:getSiblingsOfNameRange(child: Instance, NameRange: {string}): {Instance}
	assert(typeof(child) == "Instance", "Invalid argument #1 to 'getSiblingsOfNameRange' (Instance expected)")
	assert(child.Parent ~= nil, "Invalid argument #1 to 'getSiblingsOfNameRange' (Instance parent is nil)")
	assert(typeof(NameRange) == "table", "Invalid argument #2 to 'getSiblingsOfNameRange' (table expected)")

	local foundSiblings: {Instance} = {}

	for _, name: string in NameRange do
		for _, sibling: Instance in InstanceUtils:getSiblingsOfName(child, name) do
			table.insert(foundSiblings, sibling)
		end
	end

	return foundSiblings
end

function InstanceUtils:getDescendantsOfNameRange(ancestor: Instance, NameRange: {string}): {Instance}
	assert(typeof(ancestor) == "Instance", "Invalid argument #1 to 'getDescendantsOfNameRange' (Instance expected)")
	assert(typeof(NameRange) == "table", "Invalid argument #2 to 'getDescendantsOfNameRange' (table expected)")

	local foundDescendants: {Instance} = {}

	for _, name: string in NameRange do
		for _, descendant: Instance in InstanceUtils:getDescendantsOfName(ancestor, name) do
			table.insert(foundDescendants, descendant)
		end
	end

	return foundDescendants
end

function InstanceUtils:getAncestorsOfNameRange(descendant: Instance, NameRange: {string}): {Instance}
	assert(typeof(descendant) == "Instance", "Invalid argument #1 to 'getAncestorsOfNameRange' (Instance expected)")
	assert(descendant.Parent ~= nil, "Invalid argument #1 to 'getAncestorsOfNameRange' (Instance parent is nil)")
	assert(typeof(NameRange) == "table", "Invalid argument #2 to 'getAncestorsOfNameRange' (table expected)")

	local foundAncestors: {Instance} = {}

	for _, name: string in NameRange do
		for _, ancestor: Instance in InstanceUtils:getAncestorsOfName(descendant, name) do
			table.insert(foundAncestors, ancestor)
		end
	end

	return foundAncestors
end

--

function InstanceUtils:getChildrenOfClass(parent: Instance, className: string): {Instance}
	assert(typeof(parent) == "Instance", "Invalid argument #1 to 'getChildrenOfClass' (Instance expected)")
	assert(typeof(className) == "string", "Invalid argument #2 to 'getChildrenOfClass' (string expected)")

	local foundChildren: {Instance} = {}

	for _, child: Instance in parent:GetChildren() do
		if child.ClassName == className then
			table.insert(foundChildren, child)
		end
	end

	return foundChildren
end

function InstanceUtils:getSiblingsOfClass(child: Instance, className: string): {Instance}
	assert(typeof(child) == "Instance", "Invalid argument #1 to 'getSiblingsOfClass' (Instance expected)")
	assert(child.Parent ~= nil, "Invalid argument #1 to 'getSiblingsOfClass' (Instance parent is nil)")
	assert(typeof(className) == "string", "Invalid argument #2 to 'getSiblingsOfClass' (string expected)")

	local foundSiblings: {Instance} = {}

	for _, sibling: Instance in InstanceUtils:getSiblings(child) do
		if sibling.ClassName == className then
			table.insert(foundSiblings, sibling)
		end
	end

	return foundSiblings
end

function InstanceUtils:getDescendantsOfClass(ancestor: Instance, className: string): {Instance}
	assert(typeof(ancestor) == "Instance", "Invalid argument #1 to 'getDescendantsOfClass' (Instance expected)")
	assert(typeof(className) == "string", "Invalid argument #2 to 'getDescendantsOfClass' (string expected)")

	local foundDescendants: {Instance} = {}

	for _, descendant: Instance in ancestor:GetDescendants() do
		if descendant.ClassName == className then
			table.insert(foundDescendants, descendant)
		end
	end

	return foundDescendants
end

function InstanceUtils:getAncestorsOfClass(descendant: Instance, className: string): {Instance}
	assert(typeof(descendant) == "Instance", "Invalid argument #1 to 'getAncestorsOfClass' (Instance expected)")
	assert(descendant.Parent ~= nil, "Invalid argument #1 to 'getAncestorsOfClass' (Instance parent is nil)")
	assert(typeof(className) == "string", "Invalid argument #2 to 'getAncestorsOfClass' (string expected)")

	local foundAncestors: {Instance} = {}

	for _, ancestor: Instance in InstanceUtils:getAncestors(descendant) do
		if ancestor.ClassName == className then
			table.insert(foundAncestors, ancestor)
		end
	end

	return foundAncestors
end

--

function InstanceUtils:getChildrenOfClassRange(parent: Instance, classNameRange: {string}): {Instance}
	assert(typeof(parent) == "Instance", "Invalid argument #1 to 'getChildrenOfClassRange' (Instance expected)")
	assert(typeof(classNameRange) == "table", "Invalid argument #2 to 'getChildrenOfClassRange' (table expected)")

	local foundChildren: {Instance} = {}

	for _, className: string in classNameRange do
		for _, child: Instance in InstanceUtils:getChildrenOfClass(parent, className) do
			table.insert(foundChildren, child)
		end
	end

	return foundChildren
end

function InstanceUtils:getSiblingsOfClassRange(child: Instance, classNameRange: {string}): {Instance}
	assert(typeof(child) == "Instance", "Invalid argument #1 to 'getSiblingsOfClassRange' (Instance expected)")
	assert(child.Parent ~= nil, "Invalid argument #1 to 'getSiblingsOfClassRange' (Instance parent is nil)")
	assert(typeof(classNameRange) == "table", "Invalid argument #2 to 'getSiblingsOfClassRange' (table expected)")

	local foundSiblings: {Instance} = {}

	for _, className: string in classNameRange do
		for _, sibling: Instance in InstanceUtils:getSiblingsOfClass(child, className) do
			table.insert(foundSiblings, sibling)
		end
	end

	return foundSiblings
end

function InstanceUtils:getDescendantsOfClassRange(ancestor: Instance, classNameRange: {string}): {Instance}
	assert(typeof(ancestor) == "Instance", "Invalid argument #1 to 'getDescendantsOfClassRange' (Instance expected)")
	assert(typeof(classNameRange) == "table", "Invalid argument #2 to 'getDescendantsOfClassRange' (table expected)")

	local foundDescendants: {Instance} = {}

	for _, className: string in classNameRange do
		for _, descendant: Instance in InstanceUtils:getDescendantsOfClass(ancestor, className) do
			table.insert(foundDescendants, descendant)
		end
	end

	return foundDescendants
end

function InstanceUtils:getAncestorsOfClassRange(descendant: Instance, classNameRange: {string}): {Instance}
	assert(typeof(descendant) == "Instance", "Invalid argument #1 to 'getAncestorsOfClassRange' (Instance expected)")
	assert(descendant.Parent ~= nil, "Invalid argument #1 to 'getAncestorsOfClassRange' (Instance parent is nil)")
	assert(typeof(classNameRange) == "table", "Invalid argument #2 to 'getAncestorsOfClassRange' (table expected)")

	local foundAncestors: {Instance} = {}

	for _, className: string in classNameRange do
		for _, ancestor: Instance in InstanceUtils:getAncestorsOfClass(descendant, className) do
			table.insert(foundAncestors, descendant)
		end
	end

	return foundAncestors
end

--

function InstanceUtils:getChildrenOfNameAndClass(child: Instance, siblingName: string, className: string): {Instance?}

end

function InstanceUtils:getSiblingsOfNameAndClass(child: Instance, siblingName: string, className: string): {Instance?}

end

function InstanceUtils:getDescendantsOfNameAndClass(child: Instance, siblingName: string, className: string): {Instance?}

end

function InstanceUtils:getAncestorsOfNameAndClass(child: Instance, siblingName: string, className: string): {Instance?}

end

--

function InstanceUtils:getChildrenOfRangeNamesAndClasses(child: Instance, siblingNames: {string}, classNames: {string}): {Instance?}

end

function InstanceUtils:getSiblingsOfRangeNamesAndClasses(child: Instance, siblingNames: {string}, classNames: {string}): {Instance?}

end

function InstanceUtils:getDescendantsOfRangeNamesAndClasses(child: Instance, siblingNames: {string}, classNames: {string}): {Instance?}

end

function InstanceUtils:getAncestorsOfRangeNamesAndClasses(child: Instance, siblingNames: {string}, classNames: {string}): {Instance?}

end

--

function InstanceUtils:getChildrenOfNameRangeAndClass(child: Instance, siblingNames: {string}, className: string): {Instance?}

end

function InstanceUtils:getSiblingsOfNameRangeAndClass(child: Instance, siblingNames: {string}, className: string): {Instance?}

end

function InstanceUtils:getDescendantsOfNameRangeAndClass(child: Instance, siblingNames: {string}, className: string): {Instance?}

end

function InstanceUtils:getAncestorsOfNameRangeAndClass(child: Instance, siblingNames: {string}, className: string): {Instance?}

end

--

function InstanceUtils:getChildrenOfNameAndClassRange(child: Instance, siblingName: string, classNames: {string}): {Instance?}

end

function InstanceUtils:getSiblingsOfNameAndClassRange(child: Instance, siblingName: string, classNames: {string}): {Instance?}

end

function InstanceUtils:getDescendantsOfNameAndClassRange(child: Instance, siblingName: string, classNames: {string}): {Instance?}

end

function InstanceUtils:getAncestorsOfNameAndClassRange(child: Instance, siblingName: string, classNames: {string}): {Instance?}

end

--

function InstanceUtils:getChildrenThatHavePropertyKey(child: Instance, propertyKey: string): {Instance?}

end

function InstanceUtils:getSiblingsThatHavePropertyKey(child: Instance, propertyKey: string): {Instance?}

end

function InstanceUtils:getDescendantsThatHavePropertyKey(child: Instance, propertyKey: string): {Instance?}

end

function InstanceUtils:getAncestorsThatHavePropertyKey(child: Instance, propertyKey: string): {Instance?}

end

--

function InstanceUtils:getChildrenThatHavePropertyKeys(child: Instance, propertyKeys: {string}): {Instance?}

end

function InstanceUtils:getSiblingsThatHavePropertyKeys(child: Instance, propertyKeys: {string}): {Instance?}

end

function InstanceUtils:getDescendantsThatHavePropertyKeys(child: Instance, propertyKeys: {string}): {Instance?}

end

function InstanceUtils:getAncestorsThatHavePropertyKeys(child: Instance, propertyKeys: {string}): {Instance?}

end

--

function InstanceUtils:getChildrenOfProperties(parent: Instance, propertiesTable: StringKeyDictionary<any>): {Instance}
	assert(typeof(parent) == "Instance", "Invalid argument #1 to 'getChildrenOfProperties' (Instance expected)")
	assert(typeof(propertiesTable) == "table", "Invalid argument #2 to 'getChildrenOfProperties' (dictionary expected)")

	local foundChildren: {Instance} = {}

	for _, child: Instance in parent:GetChildren() do
		local childHasProperties: boolean = InstanceUtils:hasProperties(child, propertiesTable)

		if childHasProperties == true then
			table.insert(foundChildren, child)
		end
	end

	return foundChildren
end

function InstanceUtils:getSiblingsOfProperties(child: Instance, propertiesTable: StringKeyDictionary<any>): {Instance}
	assert(typeof(child) == "Instance", "Invalid argument #1 to 'getSiblingsOfProperties' (Instance expected)")
	assert(child.Parent ~= nil, "Invalid argument #1 to 'getSiblingsOfProperties' (Instance parent is nil)")
	assert(typeof(propertiesTable) == "table", "Invalid argument #2 to 'getSiblingsOfProperties' (dictionary expected)")

	local foundSiblings: {Instance} = {}

	for _, sibling: Instance in InstanceUtils:getSiblings(child) do
		local siblingHasProperties: boolean = InstanceUtils:hasProperties(sibling, propertiesTable)

		if siblingHasProperties == true then
			table.insert(foundSiblings, sibling)
		end
	end

	return foundSiblings
end

function InstanceUtils:getDescendantsOfProperties(ancestor: Instance, propertiesTable: StringKeyDictionary<any>): {Instance}
	assert(typeof(ancestor) == "Instance", "Invalid argument #1 to 'getDescendantsOfProperties' (Instance expected)")
	assert(typeof(propertiesTable) == "table", "Invalid argument #2 to 'getDescendantsOfProperties' (dictionary expected)")

	local foundDescendants: {Instance} = {}

	for _, descendant: Instance in ancestor:GetDescendants() do
		local descendantHasProperties: boolean = InstanceUtils:hasProperties(descendant, propertiesTable)

		if descendantHasProperties == true then
			table.insert(foundDescendants, descendant)
		end
	end

	return foundDescendants
end

function InstanceUtils:getAncestorsOfProperties(descendant: Instance, propertiesTable: StringKeyDictionary<any>): {Instance}
	assert(typeof(descendant) == "Instance", "Invalid argument #1 to 'getAncestorsOfProperties' (Instance expected)")
	assert(descendant.Parent ~= nil, "Invalid argument #1 to 'getAncestorsOfProperties' (Instance parent is nil)")
	assert(typeof(propertiesTable) == "table", "Invalid argument #2 to 'getAncestorsOfProperties' (dictionary expected)")

	local foundAncestors: {Instance} = {}

	for _, ancestor: Instance in InstanceUtils:getAncestors(descendant) do
		local ancestorHasProperties: boolean = InstanceUtils:hasProperties(ancestor, propertiesTable)

		if ancestorHasProperties == true then
			table.insert(foundAncestors, ancestor)
		end
	end

	return foundAncestors
end

--

--function InstanceUtils:getChildrenOfPropertiesRanges(parent: Instance, propertiesTable: StringKeyDictionary<any>): {Instance}
--	assert(typeof(parent) == "Instance", "Invalid argument #1 to 'getChildrenOfProperties' (Instance expected)")
--	assert(typeof(propertiesTable) == "table", "Invalid argument #2 to 'getChildrenOfProperties' (dictionary expected)")

--	local foundChildren: {Instance} = {}

--	for _, child: Instance in parent:GetChildren() do
--		local childHasProperties: boolean = InstanceUtils:hasProperties(child, propertiesTable)

--		if childHasProperties == true then
--			table.insert(foundChildren, child)
--		end
--	end

--	return foundChildren
--end

--function InstanceUtils:getSiblingsOfProperties(child: Instance, propertiesTable: StringKeyDictionary<any>): {Instance}
--	assert(typeof(child) == "Instance", "Invalid argument #1 to 'getSiblingsOfProperties' (Instance expected)")
--	assert(child.Parent ~= nil, "Invalid argument #1 to 'getSiblingsOfProperties' (Instance parent is nil)")
--	assert(typeof(propertiesTable) == "table", "Invalid argument #2 to 'getSiblingsOfProperties' (dictionary expected)")

--	local foundSiblings: {Instance} = {}

--	for _, sibling: Instance in InstanceUtils:getSiblings(child) do
--		local siblingHasProperties: boolean = InstanceUtils:hasProperties(sibling, propertiesTable)

--		if siblingHasProperties == true then
--			table.insert(foundSiblings, sibling)
--		end
--	end

--	return foundSiblings
--end

--function InstanceUtils:getDescendantsOfProperties(ancestor: Instance, propertiesTable: StringKeyDictionary<any>): {Instance}
--	assert(typeof(ancestor) == "Instance", "Invalid argument #1 to 'getDescendantsOfProperties' (Instance expected)")
--	assert(typeof(propertiesTable) == "table", "Invalid argument #2 to 'getDescendantsOfProperties' (dictionary expected)")

--	local foundDescendants: {Instance} = {}

--	for _, descendant: Instance in ancestor:GetDescendants() do
--		local descendantHasProperties: boolean = InstanceUtils:hasProperties(descendant, propertiesTable)

--		if descendantHasProperties == true then
--			table.insert(foundDescendants, descendant)
--		end
--	end

--	return foundDescendants
--end

--function InstanceUtils:getAncestorsOfProperties(descendant: Instance, propertiesTable: StringKeyDictionary<any>): {Instance}
--	assert(typeof(descendant) == "Instance", "Invalid argument #1 to 'getAncestorsOfProperties' (Instance expected)")
--	assert(descendant.Parent ~= nil, "Invalid argument #1 to 'getAncestorsOfProperties' (Instance parent is nil)")
--	assert(typeof(propertiesTable) == "table", "Invalid argument #2 to 'getAncestorsOfProperties' (dictionary expected)")

--	local foundAncestors: {Instance} = {}

--	for _, ancestor: Instance in InstanceUtils:getAncestors(descendant) do
--		local ancestorHasProperties: boolean = InstanceUtils:hasProperties(ancestor, propertiesTable)

--		if ancestorHasProperties == true then
--			table.insert(foundAncestors, ancestor)
--		end
--	end

--	return foundAncestors
--end

--



--
--
--

function InstanceUtils:waitForSibling(child: Instance, siblingName: string, timeOut: number?): Instance
	assert(typeof(child) == "Instance", "Invalid argument #1 to 'waitForSibling' (Instance expected)")
	assert(child.Parent ~= nil, "Invalid argument #1 to 'waitForSibling' (Instance parent is nil)")
	assert(typeof(siblingName) == "string", "Invalid argument #2 to 'waitForSibling' (string expected)")

	if timeOut ~= nil then
		assert(typeof(timeOut) == "number", "Invalid argument #3 to 'waitForSibling' (number expected)")
	end

	local foundSibling: Instance = nil

	local startTime: number = os.clock()

	repeat
		local sibling: Instance = child.Parent:WaitForChild(siblingName, timeOut)

		if sibling ~= nil and sibling ~= child then
			foundSibling = sibling
		elseif
			(
				timeOut ~= nil
					and os.clock() - startTime > timeOut
			)
				or (
					timeOut == nil
					and os.clock() - startTime > WAIT_FOR_DEFAULT_TIMEOUT
				)
		then
			break
		end

		task.wait()
	until foundSibling ~= nil

	if timeOut ~= nil then
		assert(foundSibling ~= nil, "Infinite yield possible on 'waitForSibling'")
	end

	return foundSibling
end

function InstanceUtils:waitForDescendant(ancestor: Instance, descendantName: string, timeOut: number?): Instance
	assert(typeof(ancestor) == "Instance", "Invalid argument #1 to 'waitForDescendant' (Instance expected)")
	assert(typeof(descendantName) == "string", "Invalid argument #2 to 'waitForDescendant' (string expected)")

	if timeOut ~= nil then
		assert(typeof(timeOut) == "number", "Invalid argument #3 to 'waitForDescendant' (number expected)")
	end

	local foundDescendant: Instance = nil

	local startTime: number = os.clock()

	repeat
		local descendant: Instance = InstanceUtils:findFirstDescendant(ancestor, descendantName)

		if descendant ~= nil then
			foundDescendant = descendant
		elseif
			(
				timeOut ~= nil
					and os.clock() - startTime > timeOut
			)
				or (
					timeOut == nil
					and os.clock() - startTime > WAIT_FOR_DEFAULT_TIMEOUT
				)
		then
			break
		end

		task.wait()
	until foundDescendant ~= nil

	if timeOut ~= nil then
		assert(foundDescendant ~= nil, "Infinite yield possible on 'waitForDescendant'")
	end

	return foundDescendant
end

--

function InstanceUtils:waitForChildren(child: Instance, siblingNames: {string}): ...Instance

end

function InstanceUtils:waitForSiblings(child: Instance, siblingNames: {string}): ...Instance

end

function InstanceUtils:waitForDescendants(child: Instance, siblingNames: {string}): ...Instance

end

function InstanceUtils:waitForAncestors(child: Instance, siblingNames: {string}): ...Instance

end

--

function InstanceUtils:waitForChildOfClass(child: Instance, className: string): Instance

end

function InstanceUtils:waitForSiblingOfClass(child: Instance, className: string): Instance

end

function InstanceUtils:waitForDescendantOfClass(child: Instance, className: string): Instance

end

function InstanceUtils:waitForAncestorOfClass(child: Instance, className: string): Instance

end

--

function InstanceUtils:waitForChildrenOfClass(child: Instance, className: string, waitCount: number, timeOut: number?): ...Instance

end

function InstanceUtils:waitForSiblingsOfClass(child: Instance, className: string, waitCount: number, timeOut: number?): ...Instance

end

function InstanceUtils:waitForDescendantsOfClass(child: Instance, className: string, waitCount: number, timeOut: number?): ...Instance

end

function InstanceUtils:waitForAncestorsOfClass(child: Instance, className: string, waitCount: number, timeOut: number?): ...Instance

end

--

function InstanceUtils:waitForChildrenOfClasses(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:waitForSiblingsOfClasses(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:waitForDescendantsOfClasses(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:waitForAncestorsOfClasses(child: Instance, classNames: {string}): ...Instance

end

--

function InstanceUtils:waitForChildOfClassRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForSiblingOfClassRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForDescendantOfClassRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForAncestorOfClassRange(child: Instance, classNames: {string}): Instance

end

--

function InstanceUtils:waitForChildrenOfClassRange(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:waitForSiblingsOfClassRange(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:waitForDescendantsOfClassRange(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:waitForAncestorsOfClassRange(child: Instance, classNames: {string}): ...Instance

end

--

function InstanceUtils:waitForChildOfNameAndClass(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:waitForSiblingOfNameAndClass(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:waitForDescendantOfNameAndClass(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:waitForAncestorOfNameAndClass(child: Instance, classNames: {string}): ...Instance

end

--

function InstanceUtils:waitForChildrenOfNamesAndClasses(parent: Instance, names: {string}, classNames: {string}, timeOut: number?): ...Instance
	assert(typeof(parent) == "Instance", "Invalid argument #1 to 'waitForChildrenOfNamesAndClasses' (Instance expected)")
	assert(typeof(names) == "table", "Invalid argument #2 to 'waitForChildrenOfNamesAndClasses' (table expected)")
	assert(typeof(classNames) == "table", "Invalid argument #3 to 'waitForChildrenOfNamesAndClasses' (table expected)")

	if timeOut ~= nil then
		assert(typeof(timeOut) == "number", "Invalid argument #4 to 'waitForChildrenOfNamesAndClasses' (number expected)")
	end

	local foundChildren: {[number]: Instance} = {}

	local startTime: number = os.clock()

	repeat
		for index, name in ipairs(names) do
			task.spawn(function()
				if foundChildren[index] == nil then
					assert(typeof(name) == "string", "Invalid argument #2 to 'waitForChildrenOfNamesAndClasses' (string array expected)")

					local child: Instance? = parent:WaitForChild(name)
					local className: string = classNames[index]

					assert(typeof(className) == "string", "Invalid argument #3 to 'waitForChildrenOfNamesAndClasses' (string array expected)")

					if child ~= nil and child:IsA(className) == true then
						foundChildren[index] = child
					end
				end
			end)
		end

		task.wait()

		local allFound: boolean = (#foundChildren == #names)
		if allFound == true or (timeOut ~= nil and os.clock() - startTime >= timeOut) then
			break
		end
	until false

	if timeOut ~= nil then
		for _, name: string in ipairs(names) do
			assert(#foundChildren == #names, "Infinite yield possible on 'waitForChildrenOfNamesAndClasses'")
		end
	end

	return foundSibling
end

function InstanceUtils:waitForSiblingsOfNamesAndClasses(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:waitForDescendantsOfNamesAndClasses(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:waitForAncestorsOfNamesAndClasses(child: Instance, classNames: {string}): ...Instance

end

--

function InstanceUtils:waitForChildrenOfNameRangeAndClassRange(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:waitForSiblingsOfNameRangeAndClassRange(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:waitForDescendantsOfNameRangeAndClassRange(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:waitForAncestorsOfNameRangeAndClassRange(child: Instance, classNames: {string}): ...Instance

end

--

function InstanceUtils:waitForChildOfProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForSiblingOfProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForDescendantOfProperties(ancestor: Instance, propertiesTable: StringKeyDictionary<any>): Instance
	assert(typeof(ancestor) == "Instance", "Invalid argument #1 to 'getInstancesFromTableOfProperties' (table expected)")
	assert(typeof(propertiesTable) == "table", "Invalid argument #2 to 'getInstancesFromTableOfProperties' (dictionary expected)")

	local foundInstances: {Instance} = {}

	for _, instance: Instance in searchTable do
		local childHasProperties: boolean = InstanceUtils:hasProperties(instance, propertiesTable)

		if childHasProperties == true then
			table.insert(foundInstances, instance)
		end
	end

	return foundInstances
end

function InstanceUtils:waitForAncestorOfProperties(child: Instance, classNames: {string}): Instance

end

--

function InstanceUtils:waitForChildrenOfProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForSiblingsOfProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForDescendantsOfProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForAncestorsOfProperties(child: Instance, classNames: {string}): Instance

end

--

function InstanceUtils:waitForChildOfPropertiesRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForSiblingOfPropertiesRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForDescendantOfPropertiesRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForAncestorOfPropertiesRange(child: Instance, classNames: {string}): Instance

end

--

function InstanceUtils:waitForChildrenOfPropertiesRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForSiblingsOfPropertiesRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForDescendantsOfPropertiesRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForAncestorsOfPropertiesRange(child: Instance, classNames: {string}): Instance

end

--

function InstanceUtils:waitForChildWithExistingProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForSiblingWithExistingProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForDescendantWithExistingProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForAncestorWithExistingProperties(child: Instance, classNames: {string}): Instance

end

--

function InstanceUtils:waitForChildrenWithExistingProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForSiblingsWithExistingProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForDescendantsWithExistingProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:waitForAncestorsWithExistingProperties(child: Instance, classNames: {string}): Instance

end

--
--
--

function InstanceUtils:findFirstInstanceFromTableOfProperties(searchTable: {Instance}, propertiesTable: StringKeyDictionary<any>): Instance
	assert(typeof(searchTable) == "table", "Invalid argument #1 to 'findFirstInstanceFromTableOfProperties' (Instance expected)")
	assert(typeof(propertiesTable) == "table", "Invalid argument #2 to 'findFirstInstanceFromTableOfProperties' (dictionary expected)")

	local foundInstance: Instance = nil

	for _, instance: Instance in searchTable do
		local instanceHasProperties: boolean = InstanceUtils:hasProperties(instance, propertiesTable)

		if instanceHasProperties == true then
			foundInstance = instance
			break
		end
	end

	return foundInstance
end

--

-- TODO: Make sure validateProperty method used inside of hasProperties
function InstanceUtils:findFirstSibling(child: Instance, name: string): Instance
	assert(typeof(child) == "Instance", "Invalid argument #1 to 'findFirstSibling' (Instance expected)")
	assert(child.Parent ~= nil, "Invalid argument #1 to 'findFirstSibling' (Instance parent is nil)")
	assert(typeof(name) == "string", "Invalid argument #2 to 'findFirstSibling' (string expected)")

	local foundSibling: Instance = nil

	for _, sibling: Instance in child.Parent:GetChildren() do
		if sibling ~= child then
			if sibling.Name == name then
				foundSibling = sibling
				break
			end
		end
	end

	return foundSibling
end

function InstanceUtils:findFirstDescendant(ancestor: Instance, name: string): Instance
	assert(typeof(ancestor) == "Instance", "Invalid argument #1 to 'findFirstDescendant' (Instance expected)")
	assert(typeof(name) == "string", "Invalid argument #2 to 'findFirstDescendant' (string expected)")
	
	local foundDescendant: Instance = ancestor:FindFirstChild(name, true)
	
	return foundDescendant
end

--

function InstanceUtils:findFirstChildren(child: Instance, names: {string}): ...Instance

end

function InstanceUtils:findFirstSiblings(child: Instance, names: {string}): ...Instance

end

function InstanceUtils:findFirstDescendants(child: Instance, names: {string}): ...Instance

end

function InstanceUtils:findFirstAncestors(child: Instance, names: {string}): ...Instance

end

--

function InstanceUtils:findFirstSiblingOfClass(child: Instance, className: string): Instance

end

function InstanceUtils:findFirstDescendantOfClass(child: Instance, className: string): Instance

end

--

function InstanceUtils:findFirstChildrenOfClass(child: Instance, className: string, waitCount: number, timeOut: number?): ...Instance

end

function InstanceUtils:findFirstSiblingsOfClass(child: Instance, className: string, waitCount: number, timeOut: number?): ...Instance

end

function InstanceUtils:findFirstDescendantsOfClass(child: Instance, className: string, waitCount: number, timeOut: number?): ...Instance

end

function InstanceUtils:findFirstAncestorsOfClass(child: Instance, className: string, waitCount: number, timeOut: number?): ...Instance

end

--

function InstanceUtils:findFirstChildOfNameAndClass(parent: Instance, name: string, className: string): Instance
	assert(typeof(parent) == "Instance", "Invalid argument #1 to 'findFirstChildOfNameAndClass' (Instance expected)")
	assert(typeof(name) == "string", "Invalid argument #2 to 'findFirstChildOfNameAndClass' (string expected)")
	assert(typeof(className) == "string", "Invalid argument #3 to 'findFirstChildOfNameAndClass' (string expected)")

	local foundChild: Instance = nil

	for _, child: Instance in parent:GetChildren() do
		if child.Name == name and child.ClassName == className then
			foundChild = child
			break
		end
	end

	return foundChild
end

function InstanceUtils:findFirstSiblingOfNameAndClass(child: Instance, name: string, className: string): Instance
	assert(typeof(child) == "Instance", "Invalid argument #1 to 'findFirstSiblingOfNameAndClass' (Instance expected)")
	assert(child.Parent ~= nil, "Invalid argument #1 to 'findFirstSiblingOfNameAndClass' (Instance parent is nil)")
	assert(typeof(name) == "string", "Invalid argument #2 to 'findFirstSiblingOfNameAndClass' (string expected)")
	assert(typeof(className) == "string", "Invalid argument #3 to 'findFirstSiblingOfNameAndClass' (string expected)")
	
	local foundSibling: Instance = nil

	for _, sibling: Instance in InstanceUtils:getSiblings(child) do
		if sibling.Name == name and sibling.ClassName == className then
			foundSibling = sibling
			break
		end
	end

	return foundSibling
end

function InstanceUtils:findFirstDescendantOfNameAndClass(ancestor: Instance, name: string, className: string): Instance
	assert(typeof(ancestor) == "Instance", "Invalid argument #1 to 'findFirstDescendantOfNameAndClass' (Instance expected)")
	assert(typeof(name) == "string", "Invalid argument #2 to 'findFirstDescendantOfNameAndClass' (string expected)")
	assert(typeof(className) == "string", "Invalid argument #3 to 'findFirstDescendantOfNameAndClass' (string expected)")

	local foundDescendant: Instance = nil

	for _, descendant: Instance in ancestor:GetDescendants() do
		if descendant.Name == name and descendant.ClassName == className then
			foundDescendant = descendant
			break
		end
	end

	return foundDescendant
end

function InstanceUtils:findFirstAncestorOfNameAndClass(descendant: Instance, name: string, className: string): Instance
	assert(typeof(descendant) == "Instance", "Invalid argument #1 to 'findFirstDescendantOfNameAndClass' (Instance expected)")
	assert(descendant.Parent ~= nil, "Invalid argument #1 to 'findFirstDescendantOfNameAndClass' (Instance parent is nil)")
	assert(typeof(name) == "string", "Invalid argument #2 to 'findFirstDescendantOfNameAndClass' (string expected)")
	assert(typeof(className) == "string", "Invalid argument #3 to 'findFirstDescendantOfNameAndClass' (string expected)")

	local foundAncestor: Instance = nil

	for _, ancestor: Instance in InstanceUtils:getAncestors(descendant) do
		if ancestor.Name == name and ancestor.ClassName == className then
			foundAncestor = ancestor
			break
		end
	end

	return foundAncestor
end

--

function InstanceUtils:findFirstChildrenOfClasses(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:findFirstSiblingsOfClasses(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:findFirstDescendantsOfClasses(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:findFirstAncestorsOfClasses(child: Instance, classNames: {string}): ...Instance

end

--

function InstanceUtils:findFirstChildOfClassRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstSiblingOfClassRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstDescendantOfClassRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstAncestorOfClassRange(child: Instance, classNames: {string}): Instance

end

--

function InstanceUtils:findFirstChildrenOfClassRange(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:findFirstSiblingsOfClassRange(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:findFirstDescendantsOfClassRange(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:findFirstAncestorsOfClassRange(child: Instance, classNames: {string}): ...Instance

end

--

function InstanceUtils:findFirstChildrenOfNamesAndClasses(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:findFirstSiblingsOfNamesAndClasses(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:findFirstDescendantsOfNamesAndClasses(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:findFirstAncestorsOfNamesAndClasses(child: Instance, classNames: {string}): ...Instance

end

--

function InstanceUtils:findFirstChildrenOfNameRangeAndClassRange(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:findFirstSiblingsOfNameRangeAndClassRange(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:findFirstDescendantsOfNameRangeAndClassRange(child: Instance, classNames: {string}): ...Instance

end

function InstanceUtils:findFirstAncestorsOfNameRangeAndClassRange(child: Instance, classNames: {string}): ...Instance

end

--

function InstanceUtils:findFirstChildOfProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstSiblingOfProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstDescendantOfProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstAncestorOfProperties(child: Instance, classNames: {string}): Instance

end

--

function InstanceUtils:findFirstChildrenOfProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstSiblingsOfProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstDescendantsOfProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstAncestorsOfProperties(child: Instance, classNames: {string}): Instance

end

--

function InstanceUtils:findFirstChildOfPropertiesRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstSiblingOfPropertiesRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstDescendantOfPropertiesRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstAncestorOfPropertiesRange(child: Instance, classNames: {string}): Instance

end

--

function InstanceUtils:findFirstChildrenOfPropertiesRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstSiblingsOfPropertiesRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstDescendantsOfPropertiesRange(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstAncestorsOfPropertiesRange(child: Instance, classNames: {string}): Instance

end

--

function InstanceUtils:findFirstChildWithExistingProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstSiblingWithExistingProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstDescendantWithExistingProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstAncestorWithExistingProperties(child: Instance, classNames: {string}): Instance

end

--

function InstanceUtils:findFirstChildrenWithExistingProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstSiblingsWithExistingProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstDescendantsWithExistingProperties(child: Instance, classNames: {string}): Instance

end

function InstanceUtils:findFirstAncestorsWithExistingProperties(child: Instance, classNames: {string}): Instance

end

return InstanceUtils
