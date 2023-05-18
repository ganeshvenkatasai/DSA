
## Set Matrix Zeros

```
class Solution {
public:
    void setZeroes(vector<vector<int>>& m) {
        int r=m.size(),c=m[0].size();
        int row=1;
        for(int i=0;i<c;i++) if(m[0][i]==0) row=0;
        for(int i=0;i<r;i++) if(m[i][0]==0) m[0][0]=0;
        for(int i=1;i<r;i++){
            for(int j=0;j<c;j++){
                if(i==0 && j==0) continue;
                if(m[i][j]==0){
                    m[0][j]=0;
                    m[i][0]=0;
                }
            }
        }
        for(int i=1;i<r;i++){
            for(int j=1;j<c;j++){
                if(m[0][j]==0 || m[i][0]==0){
                    m[i][j]=0;
                }
            }
        }
        for(int i=1;i<c;i++) if(row==0) m[0][i]=0;
        for(int i=0;i<r;i++) if(m[0][0]==0) m[i][0]=0;
        if(row==0) m[0][0]=0;
    }
};
```

## Set Matrix Zeros

```

```

## Set Matrix Zeros

```

```

## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```
## Set Matrix Zeros

```

```