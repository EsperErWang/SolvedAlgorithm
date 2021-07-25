Easy：

##### [278. First Bad Version](https://leetcode.com/problems/first-bad-version)

<details><summary>Show code</summary>
<pre><code>
    public int firstBadVersion(int n) {
        int first = 0;
        int last = n;
        while (last > first + 1) {
            int mid = first + (last - first) / 2;
            if (isBadVersion(mid)) {
                last = mid;
            }else {
                first = mid;
            }
        }
        return isBadVersion(first) ? first : last;       
    }
</code></pre></details>

**[374. Guess Number Higher or Lower](https://leetcode.com/problems/guess-number-higher-or-lower)**

<details><summary>Show code</summary>
<pre><code>
    public int guessNumber(int n) {
        int left = 0;
        int right = n;
        while (right > left + 1) {
            int mid = left + (right - left) / 2;
            if (guess(mid) == 1) {
                left = mid;
            }else if (guess(mid) == -1) {
                right = mid;
            }else {
                return mid;
            }
        }
        return guess(left) == 0 ? left : right;
    }
</code></pre></details>

