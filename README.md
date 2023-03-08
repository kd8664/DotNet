# Bechmark dotnet

This benchmark shows how fast cpu process TryCatchParse vs TryParse.
And also the benchmark will show which method is better and how much memory this or that method takes.

|               Method |        Mean |     Error |    StdDev | Rank |   Gen0 | Allocated |
|--------------------- |------------:|----------:|----------:|-----:|-------:|----------:|
|       ParseWithError | 8,848.09 ns | 42.623 ns | 33.277 ns |    4 | 0.1221 |     560 B |
|    TryParseWithError |    11.68 ns |  0.215 ns |  0.201 ns |    1 |      - |         - |
|    ParseWithOutError |    18.99 ns |  0.104 ns |  0.081 ns |    3 |      - |         - |
| TryParseWithOutError |    14.78 ns |  0.316 ns |  0.296 ns |    2 |      - |         - |

