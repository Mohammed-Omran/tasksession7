## How javascript work?
1. First item there is engines that make js work (المحركات تعتبر قلب لأي لغة وهى تعتبر البرنامج الرئيسي الى بيقوم بقرائة كود الجافا سكريبت وينفذه)
2. Second item Lexical analysis (مرحلة التحليل) :
    * First item scanning and this is made by parser (interpreterيعتبر الوحدة المبسطة من ال) -> parser breaks the code into tokens or chunks (this stage is called tokenization)
    * Second item parser remove comments and spaces because it does not need it
    * Third item parser made error handling to send the code clear
    * Fourth item after made previous 3 stages parser send the clear code as token stream
3. Third item AST (Abstract Syntax Tree) which is a hierarchical representation of the code's structure which helps the engine understand the relationships between different parts of the code.
4. Fourth item AST Traversal (in this stage the language start to understand the tree)
4. Fifth item execution to execute the code
4. Sixth item show results to the user
---
## what is document.write and it's job?
it is a method in JavaScript that allows you to dynamically write content directly to a web page , It's a simple way to generate content, such as text, HTML elements, or even script tags, and have it appear in the rendered HTML.
