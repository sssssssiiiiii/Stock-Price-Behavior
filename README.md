# Assignment 1 — Analyzing Twitter Cashtags and Stock Market Data
This project explores how financial discussions on Twitter, specifically **cashtags** (e.g., `$TSLA`, `$AAPL`), relate to stock market behavior.  
I integrate a real-world Twitter dataset with stock price data to analyze whether tweet volume correlates with stock movement.

## Index Optimization
To improve performance for filtering and joins, I added B-tree indexes on `symbol` and `day`.

I plotted a dual-axis chart:
- **Left Y-axis**: Tweet count (bars)
- **Right Y-axis**: Average open price (line)

This shows how social media volume and stock movement may relate over time.

## Key Skills Demonstrated

- Relational database design & SQL
- Materialized views and indexing in PostgreSQL
- Data joining & cleaning with Python
- Visualization of temporal financial/social data
- Big data framing using 4Vs
