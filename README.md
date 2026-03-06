# ⚡ C++ Competitive Programming Template & Snippets

This repository contains a **fast C++ template** and a collection of **VS Code snippets** designed to speed up writing solutions during competitive programming contests.

The snippets help reduce typing and allow you to focus on the algorithm instead of boilerplate code.

---

# 🚀 Main Template

Trigger with:

```
cp
```

Then press **Tab**

```cpp
#include <bits/stdc++.h>
using namespace std;

#define f ios::sync_with_stdio(false); cin.tie(NULL); cout.tie(NULL);

#define ll long long
#define ld long double

#define pb push_back
#define eb emplace_back
#define all(x) x.begin(), x.end()
#define rall(x) x.rbegin(), x.rend()

#define F first
#define S second

const int M = 1e9+7;
const int N = 2e5+5;

using vi = vector<int>;
using vll = vector<long long>;
using pii = pair<int,int>;
using pll = pair<long long,long long>;

void solve(){
    
}

int main(){
    f

    int t = 1;
    cin >> t;

    while(t--){
        solve();
    }
}
```

---

# ⚡ Macros Explained

| Macro     | Meaning            |
| --------- | ------------------ |
| `f`       | Fast input/output  |
| `ll`      | long long          |
| `ld`      | long double        |
| `pb`      | push_back          |
| `eb`      | emplace_back       |
| `all(x)`  | x.begin(), x.end() |
| `rall(x)` | reverse iterator   |
| `F`       | first (pair)       |
| `S`       | second (pair)      |

---

# 📦 STL Aliases

| Alias | Type                      |
| ----- | ------------------------- |
| `vi`  | vector<int>               |
| `vll` | vector<long long>         |
| `pii` | pair<int,int>             |
| `pll` | pair<long long,long long> |

---

# 🔁 Loop Snippets

### Forward Loop

Prefix

```
fr
```

Expands to

```cpp
for(int i = 0; i < n; i++){

}
```

---

### Reverse Loop

Prefix

```
rf
```

Expands to

```cpp
for(int i = n; i >= 0; i--){

}
```

---

# 📦 Container Snippets

### Vector

Prefix

```
v
```

Expands to

```cpp
vector<int> v(n);
```

---

### Set

Prefix

```
st
```

Expands to

```cpp
set<int> s;
```

---

### Map

Prefix

```
mp
```

Expands to

```cpp
map<int,int> mp;
```

---

### Priority Queue

Prefix

```
pq
```

Expands to

```cpp
priority_queue<int> pq;
```

---

# 📥 Input Snippets

### Vector Input

Prefix

```
vin
```

Expands to

```cpp
for(auto &x : v) cin >> x;
```

---

# 🔄 Container Operations

### Sort

Prefix

```
s
```

```cpp
sort(all(v));
```

---

### Reverse

Prefix

```
rv
```

```cpp
reverse(all(v));
```

---

# 🔎 Binary Search Template

Prefix

```
bs
```

Expands to

```cpp
int l = 0, r = n - 1;

while(l <= r){
    int mid = (l + r) / 2;

    if(condition){
        r = mid - 1;
    }else{
        l = mid + 1;
    }
}
```

---

# 📉 Minimum Operations

### Vector Minimum

Prefix

```
minv
```

```cpp
*min_element(v.begin(), v.end())
```

---

### Set Minimum

Prefix

```
mins
```

```cpp
*s.begin()
```

---

### Map Minimum Key

Prefix

```
minmk
```

```cpp
mp.begin()->first
```

---

### Map Minimum Value

Prefix

```
minmv
```

```cpp
mp.begin()->second
```

---

# 📈 Maximum Operations

### Vector Maximum

Prefix

```
maxv
```

```cpp
*max_element(v.begin(), v.end())
```

---

### Set Maximum

Prefix

```
maxs
```

```cpp
*s.rbegin()
```

---

### Map Maximum Key

Prefix

```
maxmk
```

```cpp
mp.rbegin()->first
```

---

### Map Maximum Value

Prefix

```
maxmv
```

```cpp
mp.rbegin()->second
```

---

# 📊 Min + Max Together

Prefix

```
mmv
```

Expands to

```cpp
auto [mn, mx] = minmax_element(v.begin(), v.end());
```

---

# 🧠 Most Used Shortcuts

```
cp
fr
v
vin
s
rv
bs
minv
maxv
```

These are the shortcuts you will use most during contests.

---

# 💡 Competitive Programming Tips

• Use short variable names
• Use fast IO (`f`)
• Use `all()` with STL algorithms
• Pre-write common structures with snippets
• Focus on algorithm design rather than typing speed

---

# 📚 Useful STL Algorithms

| Algorithm     | Usage                      |
| ------------- | -------------------------- |
| sort          | sorting                    |
| reverse       | reverse container          |
| min_element   | find minimum               |
| max_element   | find maximum               |
| binary_search | search in sorted container |
| lower_bound   | first element ≥ value      |
| upper_bound   | first element > value      |

---

# 🏁 Future Improvements

Possible snippets to add later:

* DFS
* BFS
* Dijkstra
* DSU
* Segment Tree
* Prefix Sum
* Two Pointers
* Sliding Window

These will make the template even faster during contests.

---

⭐ Tip: Keep this README open during practice for quick reference.
