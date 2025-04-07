
### 🧩 Maze Solver – Coin Collector Edition

This Python program solves a coin-collecting maze using **Depth-First Search (DFS)**.  

You begin at the **starting point `S`** and aim to reach the **goal `G`**, collecting as many coins as possible along the way. The total number of coins collected is the **solution**.

#### 🧱 Maze Structure

- `S`: Start position  
- `G`: Goal position  
- `X`: Wall (cannot pass through)  
- `0`–`9`: Coin values in each cell  
- Lava surrounds the maze (stay inside!)  

#### 📄 Example Input (Text File)

```
G503746
0XXXXX4
3XS6138
3XXXXXX
1X19736
5XXXXX8
3375042
```

#### ✅ Sample Solution Path
```
S → 6 → 1 → 3 → 8 → 4 → 6 → 4 → 7 → 3 → 0 → G
```

**Coins collected** = `6 + 1 + 3 + 8 + 4 + 6 + 4 + 7 + 3 + 0 + 5` = **47**

---
