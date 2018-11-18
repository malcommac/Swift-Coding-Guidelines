# Swift Coding Guidelines

The following section describe a list of rules, code conducts and best practices used while working on iOS projects using Swift language.
With the help of a set of shared guidelines and automated tools we aim to maintain a higher level of code discipline and increase the reliability of the code during the entire lifecycle of a project.

The following section describe tools and rules used into the project.
In order to automate the check of the source code by identifying some common and uncommon mistakes [SwiftLint](https://github.com/realm/SwiftLint) tool is used and executed at each build of the project.

## Index
- [Code Formatting](1.Code_Formatting.md)
- [Naming Conventions](2.Naming_Conventions.md)
    - [Naming Conventions for Code](2.Naming_Conventions.md#code)
    - [File Naming Conventions](2.Naming_Conventions.md#files)
- [Coding Style](3.Coding_Style.md)
    - [General Guidelines](3.Coding_Style.md#general_guidelines)
    - [Variables](3.Coding_Style.md#variables)
    - [Constants](3.Coding_Style.md#constants)
    - [Tuples](3.Coding_Style.md#tuples)
    - [Access Modifiers](3.Coding_Style.md#access_modifiers)
    - [Custom Operators](3.Coding_Style.md#custom_operators)
    - [Switch & Enums](3.Coding_Style.md#switch_enums)
    - [Optionals](3.Coding_Style.md#optionals)
    - [Protocols](3.Coding_Style.md#protocols)
    - [Properties](3.Coding_Style.md#properties)
    - [Ternary Operator](3.Coding_Style.md#ternary_operator)
    - [Closures](3.Coding_Style.md#closures)
    - [Delegates](3.Coding_Style.md#delegates)
    - [Array](3.Coding_Style.md#array)
    - [Using `guard`](3.Coding_Style.md#guard)
    - [Error Handling](3.Coding_Style.md#error_handling)
    - [Unused Code](3.Coding_Style.md#unused_code)
    - [Importing Modules](3.Coding_Style.md#importing_modules)
    - [Using of `self`](3.Coding_Style.md#using_self)
    - [Classes or Structs](3.Coding_Style.md#classes_structs)
    - [Loops](3.Coding_Style.md#loops)
    - [Documentation & Comments](3.Coding_Style.md#doc_comments)
- [Linter Rules](4.SwiftLint_Rules.md)

### References

The following documents are used as base for this set of rules.
- [Raywenderlich Swift Guidelines](https://github.com/raywenderlich/swift-style-guide)
- [LinkedIn Swift Style Guide](https://github.com/linkedin/swift-style-guide)
- [Github Swift Style Guide](https://google.github.io/swift/)
- [Apple Swift API Design Guidelines](https://swift.org/documentation/api-design-guidelines/)
