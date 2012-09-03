BlockSample-Objective-C
=======================

Blocks are a nonstandard extension added by Apple Inc. to the, C++, and Objective-C programming languages that uses a lambda expression-like syntax to create closures within these languages. Blocks are supported for programs developed for Mac OS X 10.6+ and iOS 4.0+. Apple designed blocks with the explicit goal of making it easier to write programs for the Grand Central Dispatch threading architecture, although it is independent of that architecture and can be used in much the same way as closures in other languages. Apple has implemented blocks both in their own branch of the GNU Compiler Collection and in the Clang LLVM compiler front end. Language runtime library support for blocks is also available as part of the LLVM project. Like function definitions, blocks can take arguments, and declare their own variables internally. Unlike ordinary C function definitions, their value can capture state from their surrounding context. A block definition produces an opaque value which contains both a reference to the code within the block and a snapshot of the current state of local stack variables at the time of its definition. The block may be later invoked in the same manner as a function pointer. The block may be assigned to variables, passed to functions, and otherwise treated like a normal function pointer, although the application programmer (or the API) must mark the block with a special operator (Block_copy) if it's to be used outside the scope in which it was defined. Given a block value, the code within the block can be executed at any later time by calling it, using the same syntax that would be used for calling a function.  Why Use Blocks? Blocks are objects that encapsulate a unit of work—or, in less abstract terms, a segment of code—that can be executed at any time. They are essentially portable and anonymous functions that one can pass in as arguments of methods and functions or that can be returned from methods and functions. Blocks themselves have a typed argument list and may have inferred or declared returned type. You may also assign a block to a variable and then call it just as you would a function. The caret symbol (^) is used as a syntactic marker for blocks.The sample demonstrates different usage of Blocks in objective-c.