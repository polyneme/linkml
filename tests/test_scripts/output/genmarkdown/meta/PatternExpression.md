
# Class: pattern_expression


a regular expression pattern used to evaluate conformance of a string

URI: [linkml:PatternExpression](https://w3id.org/linkml/PatternExpression)


[![img](https://yuml.me/diagram/nofunky;dir:TB/class/[SubsetDefinition],[TypeExpression]++-%20structured_pattern%200..1>[PatternExpression&#124;syntax:string%20%3F;interpolated:boolean%20%3F;partial_match:boolean%20%3F;description:string%20%3F;title:string%20%3F;deprecated:string%20%3F;todos:string%20*;notes:string%20*;comments:string%20*;from_schema:uri%20%3F;imported_from:string%20%3F;source:uriorcurie%20%3F;in_language:string%20%3F;see_also:uriorcurie%20*;deprecated_element_has_exact_replacement:uriorcurie%20%3F;deprecated_element_has_possible_replacement:uriorcurie%20%3F],[SlotExpression]++-%20structured_pattern%200..1>[PatternExpression],[PatternExpression]uses%20-.->[Extensible],[PatternExpression]uses%20-.->[Annotatable],[PatternExpression]uses%20-.->[CommonMetadata],[TypeExpression],[SlotExpression],[Extension],[Extensible],[Example],[Definition],[CommonMetadata],[Annotation],[Annotatable],[AltDescription])](https://yuml.me/diagram/nofunky;dir:TB/class/[SubsetDefinition],[TypeExpression]++-%20structured_pattern%200..1>[PatternExpression&#124;syntax:string%20%3F;interpolated:boolean%20%3F;partial_match:boolean%20%3F;description:string%20%3F;title:string%20%3F;deprecated:string%20%3F;todos:string%20*;notes:string%20*;comments:string%20*;from_schema:uri%20%3F;imported_from:string%20%3F;source:uriorcurie%20%3F;in_language:string%20%3F;see_also:uriorcurie%20*;deprecated_element_has_exact_replacement:uriorcurie%20%3F;deprecated_element_has_possible_replacement:uriorcurie%20%3F],[SlotExpression]++-%20structured_pattern%200..1>[PatternExpression],[PatternExpression]uses%20-.->[Extensible],[PatternExpression]uses%20-.->[Annotatable],[PatternExpression]uses%20-.->[CommonMetadata],[TypeExpression],[SlotExpression],[Extension],[Extensible],[Example],[Definition],[CommonMetadata],[Annotation],[Annotatable],[AltDescription])

## Uses Mixin

 *  mixin: [Extensible](Extensible.md) - mixin for classes that support extension
 *  mixin: [Annotatable](Annotatable.md) - mixin for classes that support annotations
 *  mixin: [CommonMetadata](CommonMetadata.md) - Generic metadata shared across definitions

## Referenced by Class

 *  **[Definition](Definition.md)** *[structured_pattern](structured_pattern.md)*  <sub>0..1</sub>  **[PatternExpression](PatternExpression.md)**

## Attributes


### Own

 * [syntax](syntax.md)  <sub>0..1</sub>
     * Description: the string value of the slot must conform to this regular expression expressed in the string. May be interpolated.
     * Range: [String](types/String.md)
 * [interpolated](interpolated.md)  <sub>0..1</sub>
     * Description: if true then the pattern is first string interpolated
     * Range: [Boolean](types/Boolean.md)
 * [partial_match](partial_match.md)  <sub>0..1</sub>
     * Description: if true then the pattern must match the whole string, as if enclosed in ^...$
     * Range: [Boolean](types/Boolean.md)

### Mixed in from extensible:

 * [extensions](extensions.md)  <sub>0..\*</sub>
     * Description: a tag/text tuple attached to an arbitrary element
     * Range: [Extension](Extension.md)

### Mixed in from annotatable:

 * [annotations](annotations.md)  <sub>0..\*</sub>
     * Description: a collection of tag/text tuples with the semantics of OWL Annotation
     * Range: [Annotation](Annotation.md)

### Mixed in from common_metadata:

 * [description](description.md)  <sub>0..1</sub>
     * Description: a description of the element's purpose and use
     * Range: [String](types/String.md)
     * in subsets: (basic)

### Mixed in from common_metadata:

 * [alt_descriptions](alt_descriptions.md)  <sub>0..\*</sub>
     * Range: [AltDescription](AltDescription.md)
     * in subsets: (basic)

### Mixed in from common_metadata:

 * [title](title.md)  <sub>0..1</sub>
     * Description: the official title of the element
     * Range: [String](types/String.md)
     * in subsets: (owl,basic)

### Mixed in from common_metadata:

 * [deprecated](deprecated.md)  <sub>0..1</sub>
     * Description: Description of why and when this element will no longer be used
     * Range: [String](types/String.md)
     * in subsets: (basic)

### Mixed in from common_metadata:

 * [todos](todos.md)  <sub>0..\*</sub>
     * Description: Outstanding issue that needs resolution
     * Range: [String](types/String.md)
     * in subsets: (basic)

### Mixed in from common_metadata:

 * [notes](notes.md)  <sub>0..\*</sub>
     * Description: editorial notes about an element intended for internal consumption
     * Range: [String](types/String.md)
     * in subsets: (owl,basic)

### Mixed in from common_metadata:

 * [comments](comments.md)  <sub>0..\*</sub>
     * Description: notes and comments about an element intended for external consumption
     * Range: [String](types/String.md)
     * in subsets: (owl,basic)

### Mixed in from common_metadata:

 * [examples](examples.md)  <sub>0..\*</sub>
     * Description: example usages of an element
     * Range: [Example](Example.md)
     * in subsets: (owl,basic)

### Mixed in from common_metadata:

 * [in_subset](in_subset.md)  <sub>0..\*</sub>
     * Description: used to indicate membership of a term in a defined subset of terms used for a particular domain or application (e.g. the translator_minimal subset holding the minimal set of predicates used in a translator knowledge graph)
     * Range: [SubsetDefinition](SubsetDefinition.md)
     * in subsets: (basic)

### Mixed in from common_metadata:

 * [from_schema](from_schema.md)  <sub>0..1</sub>
     * Description: id of the schema that defined the element
     * Range: [Uri](types/Uri.md)

### Mixed in from common_metadata:

 * [imported_from](imported_from.md)  <sub>0..1</sub>
     * Description: the imports entry that this element was derived from.  Empty means primary source
     * Range: [String](types/String.md)

### Mixed in from common_metadata:

 * [source](source.md)  <sub>0..1</sub>
     * Description: A related resource from which the element is derived.
     * Range: [Uriorcurie](types/Uriorcurie.md)
     * in subsets: (basic)

### Mixed in from common_metadata:

 * [in_language](in_language.md)  <sub>0..1</sub>
     * Range: [String](types/String.md)

### Mixed in from common_metadata:

 * [see_also](see_also.md)  <sub>0..\*</sub>
     * Description: a reference
     * Range: [Uriorcurie](types/Uriorcurie.md)
     * in subsets: (owl,basic)

### Mixed in from common_metadata:

 * [deprecated element has exact replacement](deprecated_element_has_exact_replacement.md)  <sub>0..1</sub>
     * Description: When an element is deprecated, it can be automatically replaced by this uri or curie
     * Range: [Uriorcurie](types/Uriorcurie.md)

### Mixed in from common_metadata:

 * [deprecated element has possible replacement](deprecated_element_has_possible_replacement.md)  <sub>0..1</sub>
     * Description: When an element is deprecated, it can be potentially replaced by this uri or curie
     * Range: [Uriorcurie](types/Uriorcurie.md)
