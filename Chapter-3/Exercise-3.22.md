# Exercise 3.22

What happens if we compute `mid` as follows:

```cpp
vector<int>::iterator mid = (vi.begin() + vi.end()) / 2;
```

**Answer**: If we compute mid as (vi.begin() + vi.end()) / 2, we will get a compilation error. This is because vi.begin() returns an iterator to the first element in the vector and vi.end() returns an iterator to the past-the-end element in the vector. When we add these iterators, we get an iterator pointing to the position one past the end of the vector..
