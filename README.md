# RestfulQL Specification (draft)

GraphQL stands out by allowing clients to specify exactly what data they want to retrieve in a single request, reducing both over-fetching and under-fetching. However, it can run into challenges with deeply nested queries and there are known performance concerns that require careful handling or specific optimizations.

REST APIs emphasize resource-oriented design with clear separation of concerns and predictable URL structures. It makes them well-suited for straightforward CRUD operations. Their alignment with HTTP semantics also supports mature caching and status handling, giving backend developers more explicit control over resource management and optimization.

As your application grows and scales, you’ll often find that relying solely on either approach falls short. That’s why I aim to combine the best aspects of both worlds and bringing hybrid data fetching to REST APIs and call this approach RestfulQL.
