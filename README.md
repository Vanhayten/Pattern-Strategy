# Pattern-Strategy

## Part 1
- Basic interface `Strategy`
- Basic `Context` implementation with `DefaultStrategyImpl`
- Static execution in `Main`

## Part 2
- Adding multiple concrete implementations (`StrategyImpl1`, `StrategyImpl2`, `StrategyImpl3`)
- Testing them by changing the strategy at runtime statically

## Part 3
- Dynamic strategy instantiation using Reflection (`Class.forName()`)
- Dictionary/Map used as a cache to avoid recreating strategy objects
- Interactive loop using `Scanner` to select strategy at runtime
