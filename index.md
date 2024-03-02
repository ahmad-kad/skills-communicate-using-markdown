# Header 1
## Header 2
### Header 3

#### Header 4
##### Header 5
###### Header 6


### Add Image
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)


### Add Codeblock
``` python
public static int zeroBinSearch(int[] a, int[] b){
        int left = 0;
        int right = b.length - 1;
        
        while (left <= right) {
            int midIdx = left + (right - left) / 2;
    
            if (b[midIdx] == 0) {
                System.out.println("Zero Found at index: " + midIdx);
                return midIdx;
            } else if (b[midIdx] < a[midIdx]) {
                //System.out.println("LHS");
                right = midIdx - 1;
            } else {
                //System.out.println("RHS");
                left = midIdx + 1;
            }
        }
        return -1;
    }
```

### Add task list

- [ ] Get Data
- [ ] Train Model
- [ ] Profit
