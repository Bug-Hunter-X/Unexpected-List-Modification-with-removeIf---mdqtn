# Kotlin `removeIf()` Gotcha: In-place Modification

This example demonstrates a potential pitfall when using the `removeIf()` function in Kotlin.  `removeIf()` modifies the list directly, which can lead to unexpected behavior if not handled correctly.  The solution showcases a safer approach using `filterNot()` to create a new list.