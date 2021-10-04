# cpp-template-engine

## Approach

1. Take string document object model as input
2. Parse DOM string and return a traversable DOM tree
3. Traverse DOM tree using (post order traversal)[]
4. Check if innerHtml of each node has handle bars
5. Evaluate handlebars using a emendable Javascript engine
6. Replace handlebars content with static string
7. Stringify DOM tree
8. Return HTML string/file
