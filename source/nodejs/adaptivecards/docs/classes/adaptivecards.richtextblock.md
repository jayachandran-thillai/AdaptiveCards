[Adaptive Cards Javascript SDK](../README.md) / [adaptivecards](../modules/adaptivecards.md) / RichTextBlock

# Class: RichTextBlock

[adaptivecards](../modules/adaptivecards.md).RichTextBlock

## Hierarchy

* [*CardElement*](card_elements.cardelement.md)

  ↳ **RichTextBlock**

## Table of contents

### Constructors

- [constructor](adaptivecards.richtextblock.md#constructor)

### Properties

- [\_parent](adaptivecards.richtextblock.md#_parent)
- [\_renderedElement](adaptivecards.richtextblock.md#_renderedelement)
- [customCssSelector](adaptivecards.richtextblock.md#customcssselector)
- [forElementId](adaptivecards.richtextblock.md#forelementid)
- [height](adaptivecards.richtextblock.md#height)
- [horizontalAlignment](adaptivecards.richtextblock.md#horizontalalignment)
- [id](adaptivecards.richtextblock.md#id)
- [maxVersion](adaptivecards.richtextblock.md#maxversion)
- [onPreProcessPropertyValue](adaptivecards.richtextblock.md#onpreprocesspropertyvalue)
- [separator](adaptivecards.richtextblock.md#separator)
- [spacing](adaptivecards.richtextblock.md#spacing)
- [defaultMaxVersion](adaptivecards.richtextblock.md#defaultmaxversion)
- [heightProperty](adaptivecards.richtextblock.md#heightproperty)
- [horizontalAlignmentProperty](adaptivecards.richtextblock.md#horizontalalignmentproperty)
- [idProperty](adaptivecards.richtextblock.md#idproperty)
- [isVisibleProperty](adaptivecards.richtextblock.md#isvisibleproperty)
- [langProperty](adaptivecards.richtextblock.md#langproperty)
- [onRegisterCustomProperties](adaptivecards.richtextblock.md#onregistercustomproperties)
- [requiresProperty](adaptivecards.richtextblock.md#requiresproperty)
- [separatorProperty](adaptivecards.richtextblock.md#separatorproperty)
- [spacingProperty](adaptivecards.richtextblock.md#spacingproperty)
- [typeNameProperty](adaptivecards.richtextblock.md#typenameproperty)

### Accessors

- [allowCustomPadding](adaptivecards.richtextblock.md#allowcustompadding)
- [defaultStyle](adaptivecards.richtextblock.md#defaultstyle)
- [hasVisibleSeparator](adaptivecards.richtextblock.md#hasvisibleseparator)
- [hostConfig](adaptivecards.richtextblock.md#hostconfig)
- [index](adaptivecards.richtextblock.md#index)
- [isInline](adaptivecards.richtextblock.md#isinline)
- [isInteractive](adaptivecards.richtextblock.md#isinteractive)
- [isStandalone](adaptivecards.richtextblock.md#isstandalone)
- [isVisible](adaptivecards.richtextblock.md#isvisible)
- [lang](adaptivecards.richtextblock.md#lang)
- [parent](adaptivecards.richtextblock.md#parent)
- [renderedElement](adaptivecards.richtextblock.md#renderedelement)
- [requires](adaptivecards.richtextblock.md#requires)
- [separatorElement](adaptivecards.richtextblock.md#separatorelement)
- [separatorOrientation](adaptivecards.richtextblock.md#separatororientation)
- [useDefaultSizing](adaptivecards.richtextblock.md#usedefaultsizing)

### Methods

- [addInline](adaptivecards.richtextblock.md#addinline)
- [adjustRenderedElementSize](adaptivecards.richtextblock.md#adjustrenderedelementsize)
- [applyPadding](adaptivecards.richtextblock.md#applypadding)
- [asString](adaptivecards.richtextblock.md#asstring)
- [createPlaceholderElement](adaptivecards.richtextblock.md#createplaceholderelement)
- [getActionAt](adaptivecards.richtextblock.md#getactionat)
- [getActionById](adaptivecards.richtextblock.md#getactionbyid)
- [getActionCount](adaptivecards.richtextblock.md#getactioncount)
- [getAllInputs](adaptivecards.richtextblock.md#getallinputs)
- [getCustomProperty](adaptivecards.richtextblock.md#getcustomproperty)
- [getDefaultPadding](adaptivecards.richtextblock.md#getdefaultpadding)
- [getDefaultSerializationContext](adaptivecards.richtextblock.md#getdefaultserializationcontext)
- [getEffectivePadding](adaptivecards.richtextblock.md#geteffectivepadding)
- [getEffectiveStyle](adaptivecards.richtextblock.md#geteffectivestyle)
- [getEffectiveStyleDefinition](adaptivecards.richtextblock.md#geteffectivestyledefinition)
- [getElementById](adaptivecards.richtextblock.md#getelementbyid)
- [getForbiddenActionTypes](adaptivecards.richtextblock.md#getforbiddenactiontypes)
- [getHasBackground](adaptivecards.richtextblock.md#gethasbackground)
- [getImmediateSurroundingPadding](adaptivecards.richtextblock.md#getimmediatesurroundingpadding)
- [getInlineAt](adaptivecards.richtextblock.md#getinlineat)
- [getInlineCount](adaptivecards.richtextblock.md#getinlinecount)
- [getJsonTypeName](adaptivecards.richtextblock.md#getjsontypename)
- [getPadding](adaptivecards.richtextblock.md#getpadding)
- [getParentContainer](adaptivecards.richtextblock.md#getparentcontainer)
- [getResourceInformation](adaptivecards.richtextblock.md#getresourceinformation)
- [getRootElement](adaptivecards.richtextblock.md#getrootelement)
- [getRootObject](adaptivecards.richtextblock.md#getrootobject)
- [getSchema](adaptivecards.richtextblock.md#getschema)
- [getSchemaKey](adaptivecards.richtextblock.md#getschemakey)
- [getValue](adaptivecards.richtextblock.md#getvalue)
- [hasAllDefaultValues](adaptivecards.richtextblock.md#hasalldefaultvalues)
- [hasDefaultValue](adaptivecards.richtextblock.md#hasdefaultvalue)
- [indexOf](adaptivecards.richtextblock.md#indexof)
- [internalParse](adaptivecards.richtextblock.md#internalparse)
- [internalRender](adaptivecards.richtextblock.md#internalrender)
- [internalToJSON](adaptivecards.richtextblock.md#internaltojson)
- [internalValidateProperties](adaptivecards.richtextblock.md#internalvalidateproperties)
- [isAtTheVeryBottom](adaptivecards.richtextblock.md#isattheverybottom)
- [isAtTheVeryLeft](adaptivecards.richtextblock.md#isattheveryleft)
- [isAtTheVeryRight](adaptivecards.richtextblock.md#isattheveryright)
- [isAtTheVeryTop](adaptivecards.richtextblock.md#isattheverytop)
- [isBleeding](adaptivecards.richtextblock.md#isbleeding)
- [isBleedingAtBottom](adaptivecards.richtextblock.md#isbleedingatbottom)
- [isBleedingAtTop](adaptivecards.richtextblock.md#isbleedingattop)
- [isBottomElement](adaptivecards.richtextblock.md#isbottomelement)
- [isDesignMode](adaptivecards.richtextblock.md#isdesignmode)
- [isDisplayed](adaptivecards.richtextblock.md#isdisplayed)
- [isFirstElement](adaptivecards.richtextblock.md#isfirstelement)
- [isHiddenDueToOverflow](adaptivecards.richtextblock.md#ishiddenduetooverflow)
- [isLastElement](adaptivecards.richtextblock.md#islastelement)
- [isLeftMostElement](adaptivecards.richtextblock.md#isleftmostelement)
- [isRightMostElement](adaptivecards.richtextblock.md#isrightmostelement)
- [isTopElement](adaptivecards.richtextblock.md#istopelement)
- [overrideInternalRender](adaptivecards.richtextblock.md#overrideinternalrender)
- [parse](adaptivecards.richtextblock.md#parse)
- [populateSchema](adaptivecards.richtextblock.md#populateschema)
- [preProcessPropertyValue](adaptivecards.richtextblock.md#preprocesspropertyvalue)
- [remove](adaptivecards.richtextblock.md#remove)
- [removeInline](adaptivecards.richtextblock.md#removeinline)
- [render](adaptivecards.richtextblock.md#render)
- [resetDefaultValues](adaptivecards.richtextblock.md#resetdefaultvalues)
- [setCustomProperty](adaptivecards.richtextblock.md#setcustomproperty)
- [setPadding](adaptivecards.richtextblock.md#setpadding)
- [setParent](adaptivecards.richtextblock.md#setparent)
- [setShouldFallback](adaptivecards.richtextblock.md#setshouldfallback)
- [setValue](adaptivecards.richtextblock.md#setvalue)
- [shouldFallback](adaptivecards.richtextblock.md#shouldfallback)
- [shouldSerialize](adaptivecards.richtextblock.md#shouldserialize)
- [toJSON](adaptivecards.richtextblock.md#tojson)
- [truncateOverflow](adaptivecards.richtextblock.md#truncateoverflow)
- [undoOverflowTruncation](adaptivecards.richtextblock.md#undooverflowtruncation)
- [updateLayout](adaptivecards.richtextblock.md#updatelayout)
- [validateProperties](adaptivecards.richtextblock.md#validateproperties)

## Constructors

### constructor

\+ **new RichTextBlock**(): [*RichTextBlock*](card_elements.richtextblock.md)

**Returns:** [*RichTextBlock*](card_elements.richtextblock.md)

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [serialization.ts:898](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/serialization.ts#L898)

## Properties

### \_parent

• `Protected` `Optional` **\_parent**: *undefined* \| [*CardObject*](card_object.cardobject.md)

Inherited from: [CardElement](card_elements.cardelement.md).[_parent](card_elements.cardelement.md#_parent)

Defined in: [card-object.ts:64](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-object.ts#L64)

___

### \_renderedElement

• `Protected` `Optional` **\_renderedElement**: *undefined* \| HTMLElement

Inherited from: [CardElement](card_elements.cardelement.md).[_renderedElement](card_elements.cardelement.md#_renderedelement)

Defined in: [card-object.ts:65](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-object.ts#L65)

___

### customCssSelector

• `Optional` **customCssSelector**: *undefined* \| *string*

Inherited from: [CardElement](card_elements.cardelement.md).[customCssSelector](card_elements.cardelement.md#customcssselector)

Defined in: [card-elements.ts:327](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L327)

___

### forElementId

• `Optional` **forElementId**: *undefined* \| *string*

Defined in: [card-elements.ts:1363](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L1363)

___

### height

• **height**: [*CardElementHeight*](../modules/card_elements.md#cardelementheight)

Inherited from: [CardElement](card_elements.cardelement.md).[height](card_elements.cardelement.md#height)

Defined in: [card-elements.ts:53](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L53)

___

### horizontalAlignment

• **horizontalAlignment**: [*HorizontalAlignment*](../enums/enums.horizontalalignment.md)

Inherited from: [CardElement](card_elements.cardelement.md).[horizontalAlignment](card_elements.cardelement.md#horizontalalignment)

Defined in: [card-elements.ts:44](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L44)

___

### id

• `Optional` **id**: *undefined* \| *string*

Inherited from: [CardElement](card_elements.cardelement.md).[id](card_elements.cardelement.md#id)

Defined in: [card-object.ts:53](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-object.ts#L53)

___

### maxVersion

• **maxVersion**: [*Version*](serialization.version.md)

Inherited from: [CardElement](card_elements.cardelement.md).[maxVersion](card_elements.cardelement.md#maxversion)

Defined in: [serialization.ts:898](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/serialization.ts#L898)

___

### onPreProcessPropertyValue

• `Optional` **onPreProcessPropertyValue**: *undefined* \| (`sender`: [*CardObject*](card_object.cardobject.md), `property`: [*PropertyDefinition*](serialization.propertydefinition.md), `value`: *any*) => *any*

Inherited from: [CardElement](card_elements.cardelement.md).[onPreProcessPropertyValue](card_elements.cardelement.md#onpreprocesspropertyvalue)

Defined in: [card-object.ts:67](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-object.ts#L67)

___

### separator

• **separator**: *boolean*

Inherited from: [CardElement](card_elements.cardelement.md).[separator](card_elements.cardelement.md#separator)

Defined in: [card-elements.ts:50](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L50)

___

### spacing

• **spacing**: [*Spacing*](../enums/enums.spacing.md)

Inherited from: [CardElement](card_elements.cardelement.md).[spacing](card_elements.cardelement.md#spacing)

Defined in: [card-elements.ts:47](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L47)

___

### defaultMaxVersion

▪ `Static` **defaultMaxVersion**: [*Version*](serialization.version.md)

Inherited from: [CardElement](card_elements.cardelement.md).[defaultMaxVersion](card_elements.cardelement.md#defaultmaxversion)

Defined in: [serialization.ts:775](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/serialization.ts#L775)

___

### heightProperty

▪ `Readonly` `Static` **heightProperty**: [*ValueSetProperty*](serialization.valuesetproperty.md)

Inherited from: [CardElement](card_elements.cardelement.md).[heightProperty](card_elements.cardelement.md#heightproperty)

Defined in: [card-elements.ts:24](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L24)

___

### horizontalAlignmentProperty

▪ `Readonly` `Static` **horizontalAlignmentProperty**: [*EnumProperty*](serialization.enumproperty.md)<*typeof* [*HorizontalAlignment*](../enums/enums.horizontalalignment.md)\>

Inherited from: [CardElement](card_elements.cardelement.md).[horizontalAlignmentProperty](card_elements.cardelement.md#horizontalalignmentproperty)

Defined in: [card-elements.ts:32](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L32)

___

### idProperty

▪ `Readonly` `Static` **idProperty**: [*StringProperty*](serialization.stringproperty.md)

Inherited from: [CardElement](card_elements.cardelement.md).[idProperty](card_elements.cardelement.md#idproperty)

Defined in: [card-object.ts:41](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-object.ts#L41)

___

### isVisibleProperty

▪ `Readonly` `Static` **isVisibleProperty**: [*BoolProperty*](serialization.boolproperty.md)

Inherited from: [CardElement](card_elements.cardelement.md).[isVisibleProperty](card_elements.cardelement.md#isvisibleproperty)

Defined in: [card-elements.ts:22](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L22)

___

### langProperty

▪ `Readonly` `Static` **langProperty**: [*StringProperty*](serialization.stringproperty.md)

Inherited from: [CardElement](card_elements.cardelement.md).[langProperty](card_elements.cardelement.md#langproperty)

Defined in: [card-elements.ts:21](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L21)

___

### onRegisterCustomProperties

▪ `Optional` `Static` **onRegisterCustomProperties**: *undefined* \| (`sender`: [*SerializableObject*](serialization.serializableobject.md), `schema`: [*SerializableObjectSchema*](serialization.serializableobjectschema.md)) => *void*

Inherited from: [CardElement](card_elements.cardelement.md).[onRegisterCustomProperties](card_elements.cardelement.md#onregistercustomproperties)

Defined in: [serialization.ts:774](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/serialization.ts#L774)

___

### requiresProperty

▪ `Readonly` `Static` **requiresProperty**: [*SerializableObjectProperty*](serialization.serializableobjectproperty.md)

Inherited from: [CardElement](card_elements.cardelement.md).[requiresProperty](card_elements.cardelement.md#requiresproperty)

Defined in: [card-object.ts:42](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-object.ts#L42)

___

### separatorProperty

▪ `Readonly` `Static` **separatorProperty**: [*BoolProperty*](serialization.boolproperty.md)

Inherited from: [CardElement](card_elements.cardelement.md).[separatorProperty](card_elements.cardelement.md#separatorproperty)

Defined in: [card-elements.ts:23](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L23)

___

### spacingProperty

▪ `Readonly` `Static` **spacingProperty**: [*EnumProperty*](serialization.enumproperty.md)<*typeof* [*Spacing*](../enums/enums.spacing.md)\>

Inherited from: [CardElement](card_elements.cardelement.md).[spacingProperty](card_elements.cardelement.md#spacingproperty)

Defined in: [card-elements.ts:37](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L37)

___

### typeNameProperty

▪ `Readonly` `Static` **typeNameProperty**: [*StringProperty*](serialization.stringproperty.md)

Inherited from: [CardElement](card_elements.cardelement.md).[typeNameProperty](card_elements.cardelement.md#typenameproperty)

Defined in: [card-object.ts:32](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-object.ts#L32)

## Accessors

### allowCustomPadding

• `Protected`get **allowCustomPadding**(): *boolean*

**Returns:** *boolean*

Defined in: [card-elements.ts:315](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L315)

___

### defaultStyle

• `Protected`get **defaultStyle**(): *string*

**Returns:** *string*

Defined in: [card-elements.ts:323](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L323)

___

### hasVisibleSeparator

• get **hasVisibleSeparator**(): *boolean*

**Returns:** *boolean*

Defined in: [card-elements.ts:596](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L596)

___

### hostConfig

• get **hostConfig**(): [*HostConfig*](host_config.hostconfig.md)

**Returns:** [*HostConfig*](host_config.hostconfig.md)

Defined in: [card-elements.ts:557](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L557)

• set **hostConfig**(`value`: [*HostConfig*](host_config.hostconfig.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`value` | [*HostConfig*](host_config.hostconfig.md) |

**Returns:** *void*

Defined in: [card-elements.ts:571](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L571)

___

### index

• get **index**(): *number*

**Returns:** *number*

Defined in: [card-elements.ts:575](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L575)

___

### isInline

• get **isInline**(): *boolean*

**Returns:** *boolean*

Defined in: [card-elements.ts:592](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L592)

___

### isInteractive

• get **isInteractive**(): *boolean*

**Returns:** *boolean*

Defined in: [card-elements.ts:584](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L584)

___

### isStandalone

• get **isStandalone**(): *boolean*

**Returns:** *boolean*

Defined in: [card-elements.ts:588](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L588)

___

### isVisible

• get **isVisible**(): *boolean*

**Returns:** *boolean*

Defined in: [card-elements.ts:77](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L77)

• set **isVisible**(`value`: *boolean*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`value` | *boolean* |

**Returns:** *void*

Defined in: [card-elements.ts:81](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L81)

___

### lang

• get **lang**(): *undefined* \| *string*

**Returns:** *undefined* \| *string*

Defined in: [card-elements.ts:56](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L56)

• set **lang**(`value`: *undefined* \| *string*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`value` | *undefined* \| *string* |

**Returns:** *void*

Defined in: [card-elements.ts:72](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L72)

___

### parent

• get **parent**(): *undefined* \| [*CardElement*](card_elements.cardelement.md)

**Returns:** *undefined* \| [*CardElement*](card_elements.cardelement.md)

Defined in: [card-elements.ts:609](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L609)

___

### renderedElement

• get **renderedElement**(): *undefined* \| HTMLElement

**Returns:** *undefined* \| HTMLElement

Defined in: [card-object.ts:143](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-object.ts#L143)

___

### requires

• get **requires**(): [*HostCapabilities*](host_capabilities.hostcapabilities.md)

**Returns:** [*HostCapabilities*](host_capabilities.hostcapabilities.md)

Defined in: [card-object.ts:56](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-object.ts#L56)

___

### separatorElement

• get **separatorElement**(): *undefined* \| HTMLElement

**Returns:** *undefined* \| HTMLElement

Defined in: [card-elements.ts:605](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L605)

___

### separatorOrientation

• `Protected`get **separatorOrientation**(): [*Orientation*](../enums/enums.orientation.md)

**Returns:** [*Orientation*](../enums/enums.orientation.md)

Defined in: [card-elements.ts:319](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L319)

___

### useDefaultSizing

• `Protected`get **useDefaultSizing**(): *boolean*

**Returns:** *boolean*

Defined in: [card-elements.ts:311](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L311)

## Methods

### addInline

▸ **addInline**(`inline`: *string* \| [*CardElement*](card_elements.cardelement.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`inline` | *string* \| [*CardElement*](card_elements.cardelement.md) |

**Returns:** *void*

Defined in: [card-elements.ts:1392](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L1392)

___

### adjustRenderedElementSize

▸ `Protected`**adjustRenderedElementSize**(`renderedElement`: HTMLElement): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`renderedElement` | HTMLElement |

**Returns:** *void*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:236](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L236)

___

### applyPadding

▸ `Protected`**applyPadding**(): *void*

**Returns:** *void*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:255](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L255)

___

### asString

▸ **asString**(): *undefined* \| *string*

**Returns:** *undefined* \| *string*

Overrides: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:1365](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L1365)

___

### createPlaceholderElement

▸ `Protected`**createPlaceholderElement**(): HTMLElement

**Returns:** HTMLElement

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:221](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L221)

___

### getActionAt

▸ **getActionAt**(`index`: *number*): *undefined* \| [*Action*](card_elements.action.md)

#### Parameters:

Name | Type |
:------ | :------ |
`index` | *number* |

**Returns:** *undefined* \| [*Action*](card_elements.action.md)

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:412](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L412)

___

### getActionById

▸ **getActionById**(`id`: *string*): *undefined* \| [*Action*](card_elements.action.md)

#### Parameters:

Name | Type |
:------ | :------ |
`id` | *string* |

**Returns:** *undefined* \| [*Action*](card_elements.action.md)

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:547](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L547)

___

### getActionCount

▸ **getActionCount**(): *number*

**Returns:** *number*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:408](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L408)

___

### getAllInputs

▸ **getAllInputs**(`processActions?`: *boolean*): [*Input*](card_elements.input.md)[]

#### Parameters:

Name | Type | Default value |
:------ | :------ | :------ |
`processActions` | *boolean* | true |

**Returns:** [*Input*](card_elements.input.md)[]

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:535](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L535)

___

### getCustomProperty

▸ **getCustomProperty**(`name`: *string*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`name` | *string* |

**Returns:** *any*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [serialization.ts:985](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/serialization.ts#L985)

___

### getDefaultPadding

▸ `Protected`**getDefaultPadding**(): [*PaddingDefinition*](shared.paddingdefinition.md)

**Returns:** [*PaddingDefinition*](shared.paddingdefinition.md)

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:291](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L291)

___

### getDefaultSerializationContext

▸ `Protected`**getDefaultSerializationContext**(): [*BaseSerializationContext*](serialization.baseserializationcontext.md)

**Returns:** [*BaseSerializationContext*](serialization.baseserializationcontext.md)

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:217](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L217)

___

### getEffectivePadding

▸ **getEffectivePadding**(): [*PaddingDefinition*](shared.paddingdefinition.md)

**Returns:** [*PaddingDefinition*](shared.paddingdefinition.md)

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:551](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L551)

___

### getEffectiveStyle

▸ **getEffectiveStyle**(): *string*

**Returns:** *string*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:341](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L341)

___

### getEffectiveStyleDefinition

▸ **getEffectiveStyleDefinition**(): [*ContainerStyleDefinition*](host_config.containerstyledefinition.md)

**Returns:** [*ContainerStyleDefinition*](host_config.containerstyledefinition.md)

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:349](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L349)

___

### getElementById

▸ **getElementById**(`id`: *string*): *undefined* \| [*CardElement*](card_elements.cardelement.md)

#### Parameters:

Name | Type |
:------ | :------ |
`id` | *string* |

**Returns:** *undefined* \| [*CardElement*](card_elements.cardelement.md)

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:543](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L543)

___

### getForbiddenActionTypes

▸ **getForbiddenActionTypes**(): [*ActionType*](../modules/card_elements.md#actiontype)[]

**Returns:** [*ActionType*](../modules/card_elements.md#actiontype)[]

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:353](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L353)

___

### getHasBackground

▸ `Protected`**getHasBackground**(): *boolean*

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:295](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L295)

___

### getImmediateSurroundingPadding

▸ **getImmediateSurroundingPadding**(`result`: [*PaddingDefinition*](shared.paddingdefinition.md), `processTop?`: *boolean*, `processRight?`: *boolean*, `processBottom?`: *boolean*, `processLeft?`: *boolean*): *void*

#### Parameters:

Name | Type | Default value |
:------ | :------ | :------ |
`result` | [*PaddingDefinition*](shared.paddingdefinition.md) | - |
`processTop` | *boolean* | true |
`processRight` | *boolean* | true |
`processBottom` | *boolean* | true |
`processLeft` | *boolean* | true |

**Returns:** *void*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:357](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L357)

___

### getInlineAt

▸ **getInlineAt**(`index`: *number*): [*CardElement*](card_elements.cardelement.md)

#### Parameters:

Name | Type |
:------ | :------ |
`index` | *number* |

**Returns:** [*CardElement*](card_elements.cardelement.md)

Defined in: [card-elements.ts:1383](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L1383)

___

### getInlineCount

▸ **getInlineCount**(): *number*

**Returns:** *number*

Defined in: [card-elements.ts:1379](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L1379)

___

### getJsonTypeName

▸ **getJsonTypeName**(): *string*

**Returns:** *string*

Overrides: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:1375](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L1375)

___

### getPadding

▸ `Protected`**getPadding**(): *undefined* \| [*PaddingDefinition*](shared.paddingdefinition.md)

**Returns:** *undefined* \| [*PaddingDefinition*](shared.paddingdefinition.md)

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:299](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L299)

___

### getParentContainer

▸ **getParentContainer**(): *undefined* \| [*Container*](card_elements.container.md)

**Returns:** *undefined* \| [*Container*](card_elements.container.md)

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:521](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L521)

___

### getResourceInformation

▸ **getResourceInformation**(): [*IResourceInformation*](../interfaces/shared.iresourceinformation.md)[]

**Returns:** [*IResourceInformation*](../interfaces/shared.iresourceinformation.md)[]

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:539](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L539)

___

### getRootElement

▸ **getRootElement**(): [*CardElement*](card_elements.cardelement.md)

**Returns:** [*CardElement*](card_elements.cardelement.md)

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:517](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L517)

___

### getRootObject

▸ **getRootObject**(): [*CardObject*](card_object.cardobject.md)

**Returns:** [*CardObject*](card_object.cardobject.md)

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-object.ts:103](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-object.ts#L103)

___

### getSchema

▸ **getSchema**(): [*SerializableObjectSchema*](serialization.serializableobjectschema.md)

**Returns:** [*SerializableObjectSchema*](serialization.serializableobjectschema.md)

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [serialization.ts:989](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/serialization.ts#L989)

___

### getSchemaKey

▸ `Protected`**getSchemaKey**(): *string*

**Returns:** *string*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-object.ts:48](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-object.ts#L48)

___

### getValue

▸ `Protected`**getValue**(`property`: [*PropertyDefinition*](serialization.propertydefinition.md)): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`property` | [*PropertyDefinition*](serialization.propertydefinition.md) |

**Returns:** *any*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [serialization.ts:826](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/serialization.ts#L826)

___

### hasAllDefaultValues

▸ **hasAllDefaultValues**(): *boolean*

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [serialization.ts:950](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/serialization.ts#L950)

___

### hasDefaultValue

▸ **hasDefaultValue**(`property`: [*PropertyDefinition*](serialization.propertydefinition.md)): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`property` | [*PropertyDefinition*](serialization.propertydefinition.md) |

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [serialization.ts:946](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/serialization.ts#L946)

___

### indexOf

▸ **indexOf**(`cardElement`: [*CardElement*](card_elements.cardelement.md)): *number*

#### Parameters:

Name | Type |
:------ | :------ |
`cardElement` | [*CardElement*](card_elements.cardelement.md) |

**Returns:** *number*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:455](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L455)

___

### internalParse

▸ `Protected`**internalParse**(`source`: *any*, `context`: [*SerializationContext*](card_elements.serializationcontext.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`source` | *any* |
`context` | [*SerializationContext*](card_elements.serializationcontext.md) |

**Returns:** *void*

Overrides: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:1271](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L1271)

___

### internalRender

▸ `Protected`**internalRender**(): *undefined* \| HTMLElement

**Returns:** *undefined* \| HTMLElement

Overrides: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:1312](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L1312)

___

### internalToJSON

▸ `Protected`**internalToJSON**(`target`: [*PropertyBag*](../modules/serialization.md#propertybag), `context`: [*SerializationContext*](card_elements.serializationcontext.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`target` | [*PropertyBag*](../modules/serialization.md#propertybag) |
`context` | [*SerializationContext*](card_elements.serializationcontext.md) |

**Returns:** *void*

Overrides: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:1298](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L1298)

___

### internalValidateProperties

▸ **internalValidateProperties**(`context`: [*ValidationResults*](card_object.validationresults.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`context` | [*ValidationResults*](card_object.validationresults.md) |

**Returns:** *void*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-object.ts:113](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-object.ts#L113)

___

### isAtTheVeryBottom

▸ **isAtTheVeryBottom**(): *boolean*

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:485](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L485)

___

### isAtTheVeryLeft

▸ **isAtTheVeryLeft**(): *boolean*

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:473](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L473)

___

### isAtTheVeryRight

▸ **isAtTheVeryRight**(): *boolean*

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:477](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L477)

___

### isAtTheVeryTop

▸ **isAtTheVeryTop**(): *boolean*

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:481](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L481)

___

### isBleeding

▸ **isBleeding**(): *boolean*

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:337](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L337)

___

### isBleedingAtBottom

▸ **isBleedingAtBottom**(): *boolean*

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:493](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L493)

___

### isBleedingAtTop

▸ **isBleedingAtTop**(): *boolean*

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:489](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L489)

___

### isBottomElement

▸ **isBottomElement**(`element`: [*CardElement*](card_elements.cardelement.md)): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`element` | [*CardElement*](card_elements.cardelement.md) |

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:509](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L509)

___

### isDesignMode

▸ **isDesignMode**(): *boolean*

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:459](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L459)

___

### isDisplayed

▸ `Protected`**isDisplayed**(): *boolean*

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:245](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L245)

___

### isFirstElement

▸ **isFirstElement**(`element`: [*CardElement*](card_elements.cardelement.md)): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`element` | [*CardElement*](card_elements.cardelement.md) |

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:465](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L465)

___

### isHiddenDueToOverflow

▸ **isHiddenDueToOverflow**(): *boolean*

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:513](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L513)

___

### isLastElement

▸ **isLastElement**(`element`: [*CardElement*](card_elements.cardelement.md)): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`element` | [*CardElement*](card_elements.cardelement.md) |

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:469](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L469)

___

### isLeftMostElement

▸ **isLeftMostElement**(`element`: [*CardElement*](card_elements.cardelement.md)): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`element` | [*CardElement*](card_elements.cardelement.md) |

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:497](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L497)

___

### isRightMostElement

▸ **isRightMostElement**(`element`: [*CardElement*](card_elements.cardelement.md)): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`element` | [*CardElement*](card_elements.cardelement.md) |

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:501](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L501)

___

### isTopElement

▸ **isTopElement**(`element`: [*CardElement*](card_elements.cardelement.md)): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`element` | [*CardElement*](card_elements.cardelement.md) |

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:505](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L505)

___

### overrideInternalRender

▸ `Protected`**overrideInternalRender**(): *undefined* \| HTMLElement

**Returns:** *undefined* \| HTMLElement

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:251](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L251)

___

### parse

▸ **parse**(`source`: *any*, `context?`: [*SerializationContext*](card_elements.serializationcontext.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`source` | *any* |
`context?` | [*SerializationContext*](card_elements.serializationcontext.md) |

**Returns:** *void*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:329](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L329)

___

### populateSchema

▸ `Protected`**populateSchema**(`schema`: [*SerializableObjectSchema*](serialization.serializableobjectschema.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`schema` | [*SerializableObjectSchema*](serialization.serializableobjectschema.md) |

**Returns:** *void*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [serialization.ts:788](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/serialization.ts#L788)

___

### preProcessPropertyValue

▸ **preProcessPropertyValue**(`property`: [*PropertyDefinition*](serialization.propertydefinition.md), `propertyValue?`: *any*): *any*

#### Parameters:

Name | Type |
:------ | :------ |
`property` | [*PropertyDefinition*](serialization.propertydefinition.md) |
`propertyValue?` | *any* |

**Returns:** *any*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-object.ts:73](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-object.ts#L73)

___

### remove

▸ **remove**(): *boolean*

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:416](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L416)

___

### removeInline

▸ **removeInline**(`inline`: [*CardElement*](card_elements.cardelement.md)): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`inline` | [*CardElement*](card_elements.cardelement.md) |

**Returns:** *boolean*

Defined in: [card-elements.ts:1401](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L1401)

___

### render

▸ **render**(): *undefined* \| HTMLElement

**Returns:** *undefined* \| HTMLElement

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:424](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L424)

___

### resetDefaultValues

▸ **resetDefaultValues**(): *void*

**Returns:** *void*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [serialization.ts:964](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/serialization.ts#L964)

___

### setCustomProperty

▸ **setCustomProperty**(`name`: *string*, `value`: *any*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`name` | *string* |
`value` | *any* |

**Returns:** *void*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [serialization.ts:974](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/serialization.ts#L974)

___

### setPadding

▸ `Protected`**setPadding**(`value`: *undefined* \| [*PaddingDefinition*](shared.paddingdefinition.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`value` | *undefined* \| [*PaddingDefinition*](shared.paddingdefinition.md) |

**Returns:** *void*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:303](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L303)

___

### setParent

▸ **setParent**(`value`: *undefined* \| [*CardObject*](card_object.cardobject.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`value` | *undefined* \| [*CardObject*](card_object.cardobject.md) |

**Returns:** *void*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-object.ts:91](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-object.ts#L91)

___

### setShouldFallback

▸ **setShouldFallback**(`value`: *boolean*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`value` | *boolean* |

**Returns:** *void*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-object.ts:95](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-object.ts#L95)

___

### setValue

▸ `Protected`**setValue**(`property`: [*PropertyDefinition*](serialization.propertydefinition.md), `value`: *any*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`property` | [*PropertyDefinition*](serialization.propertydefinition.md) |
`value` | *any* |

**Returns:** *void*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [serialization.ts:830](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/serialization.ts#L830)

___

### shouldFallback

▸ **shouldFallback**(): *boolean*

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-object.ts:99](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-object.ts#L99)

___

### shouldSerialize

▸ `Protected`**shouldSerialize**(`context`: [*SerializationContext*](card_elements.serializationcontext.md)): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`context` | [*SerializationContext*](card_elements.serializationcontext.md) |

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:307](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L307)

___

### toJSON

▸ **toJSON**(`context?`: [*BaseSerializationContext*](serialization.baseserializationcontext.md)): *undefined* \| [*PropertyBag*](../modules/serialization.md#propertybag)

#### Parameters:

Name | Type |
:------ | :------ |
`context?` | [*BaseSerializationContext*](serialization.baseserializationcontext.md) |

**Returns:** *undefined* \| [*PropertyBag*](../modules/serialization.md#propertybag)

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [serialization.ts:916](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/serialization.ts#L916)

___

### truncateOverflow

▸ `Protected`**truncateOverflow**(`maxHeight`: *number*): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`maxHeight` | *number* |

**Returns:** *boolean*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:279](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L279)

___

### undoOverflowTruncation

▸ `Protected`**undoOverflowTruncation**(): *void*

**Returns:** *void*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:289](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L289)

___

### updateLayout

▸ **updateLayout**(`processChildren?`: *boolean*): *void*

#### Parameters:

Name | Type | Default value |
:------ | :------ | :------ |
`processChildren` | *boolean* | true |

**Returns:** *void*

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-elements.ts:450](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-elements.ts#L450)

___

### validateProperties

▸ **validateProperties**(): [*ValidationResults*](card_object.validationresults.md)

**Returns:** [*ValidationResults*](card_object.validationresults.md)

Inherited from: [CardElement](card_elements.cardelement.md)

Defined in: [card-object.ts:131](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/card-object.ts#L131)
