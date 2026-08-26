```c++
class Solution {
public:
    int mySqrt(int x) {
        int z=0;
        for(int y=0;y<=x;y++)
        if(y*y<=x && y*y+2*y+1>x){
            z=y;
        }
        return z;
    }
};
```

